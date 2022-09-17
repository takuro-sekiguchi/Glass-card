# ガラスカードの作り方

[デモサイトはこちら]()

## 改めて学んだこと
- グラデーションカラーの簡単な付け方
- ガラス感を出すには、影と白の透明度が大切
- 下の要素にブラーをかける方法
- vanilla-tilt.jsの使い方


### 下の要素にブラーをかける方法
```css
backdrop-filter: blur(5px);
```

### vanilla-tilt.jsの使い方

[vanilla-tilt.jsドキュメント](https://micku7zu.github.io/vanilla-tilt.js/)

```js
<script src="./vanilla-tilt.js"></script>
```

デフォルト設定
```js
<script type="text/javascript">
  VanillaTilt.init(document.querySelector(".card"), {
    max: 20,
    speed: 300,
  });
</script>
```

オプション
```js
{
    reverse:                false,  
    max:                    35,     
    startX:                 0,      
    startY:                 0,      
    perspective:            1000,   
    scale:                  1,      
    speed:                  300,    
    transition:             true,   
    axis:                   null,   
    reset:                  true,   
    easing:                 "cubic-bezier(.03,.98,.52,.99)",
    glare:                  false,  
    "max-glare":            1,      
    "glare-prerender":      false,  
    "mouse-event-element":  null,   
    gyroscope:              true,   
    gyroscopeMinAngleX:     -45,    
    gyroscopeMaxAngleX:     45,     
    gyroscopeMinAngleY:     -45,    
    gyroscopeMaxAngleY:     45,
}
```# Glass-card
