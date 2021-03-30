# animation

Estudando sobre animação em CSS

[Visualização](https://joaoquinto.github.io/Animation/animation/index.html)

[Fonte: Css Tricks](https://css-tricks.com/snippets/css/keyframe-animation-syntax/)

[Fonte: MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)

Basic Declaration & Usage

```css
.NAME-YOUR-ANIMATIO li {
  animation: transform-orign-scale 10s;
  animation-iteration-count: infinite;
}

@-webkit-keyframes NAME-YOUR-ANIMATION {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@-moz-keyframes NAME-YOUR-ANIMATION {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@-o-keyframes NAME-YOUR-ANIMATION {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@keyframes NAME-YOUR-ANIMATION {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
```

**_transform-origin: Informa a origem que a transformação deve começar_**

**_Scale trabalha no eixo x e y "plano cartesiano" ou seja faz crescer para cima e baixo e para esquerda e direita_**

**_Rotate trabalha com graus "deg" ou outras unids e também com x e y_**

**_Translate trabalha no x e y "plano cartesiano"_ coordenadas positivas é para baixo e para direita e negativas para cima e para a esquerda**

**_animation-iteration-count: define o tempo de interacão da animação_**
