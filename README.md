# dark past for Hugo

These files are css files, partials and shortcodes for make dark-past sites.

# How to use

## shortcodes

### Print user agents

```
あなたが使っているブラウザは{{< useragents >}}ですね？

↓

あなたが使っているブラウザはMozilla/5.0 (X11; CrOS x86_64 13099.102.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/84.0.4147.127 Safari/537.36 ですね？
```

### Print Date and time

```
只今の時刻は{{< date-time >}}です

↓

只今の時刻は2020年8月14日金曜日23時55分56秒 です
```

## partials

Add

```
{{ partial "dark-past-start.html" . }}
```

for your index.html

and set the following parameters for config.toml.

```
[params]
  music = "music/hogefuga.mp3"
  onloadMessage = "niwashiのホームページへようこそ！"
  rightClickMessage = "右クリック禁止です！"
```

Put music file in static/music/

## css

### rainbow

```
<p class="rainbow"> rainbow text </p>
```

### blink

```
<p class="blink"> blink text </p>
```

### marquee

```
<div class="marquee">
  <div class="marquee-inner"> move text </div>
</div>
```

### bigborder

```
<div class="bigborder"> text or image </div>
```

### Appearance

[Please see this homepage](https://mustyideas.tokyo/dark_past/)(be careful. Music is played on this site.)
