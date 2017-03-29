# CSS3 Effects Demos

This repo contains a set if examples using CSS3 properties to get some effects and animations

## 01. Simple Color Fade

[Demo](https://juanmaguitar.github.io/css3-examples/01-simple-color-fade/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/01-simple-color-fade)

```
transition: color 3s linear;
```

## 02. Simple Slide

[Demo](https://juanmaguitar.github.io/css3-examples/02-simple-slide/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/02-simple-slide)

```
transition: left 2s linear;
```

## 03. Simple Slide Practical

[Demo](https://juanmaguitar.github.io/css3-examples/03-simple-slide-practical/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/03-simple-slide-practical)

```
transition: left .3s linear;
```

## 04. Gradients

[Demo](https://juanmaguitar.github.io/css3-examples/04-gradients/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/04-gradients)

```
background: linear-gradient(to right, #000, #FFF);
```

## 05. Reflections

[Demo](https://juanmaguitar.github.io/css3-examples/05-reflections/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/05-reflections)

```
-webkit-box-reflect: below 0px -webkit-linear-gradient(bottom, white 0%, transparent 50%, transparent 100%);
```

## 06. Sliding Doors

[Demo](https://juanmaguitar.github.io/css3-examples/06-sliding-doors/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/06-sliding-doors)

```
transition: left .6s linear;
```

## 07. Masks

[Demo](https://juanmaguitar.github.io/css3-examples/07-masks/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/07-masks)

```
-webkit-mask-box-image: url(../img/letter-a.png);
```

## 08. Useless Rotate

[Demo](https://juanmaguitar.github.io/css3-examples/08-useless-rotate/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/08-useless-rotate)

```
img {
  transition: transform 1s linear;
  &:hover {
    transform: rotate(180deg);
  }
}
```

## 09. Simple Rotate Scale

[Demo](https://juanmaguitar.github.io/css3-examples/09-simple-rotate-scale/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/09-simple-rotate-scale)

```
@keyframes pulse {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(180deg) scale(2);
  }
}
.pulse {
  animation: pulse 4s alternate 2;
  ...
}

```


## 10. Advanced Rotate Scale

[Demo](https://juanmaguitar.github.io/css3-examples/10-advanced-rotate-scale/) | [Code](https://github.com/juanmaguitar/css3-examples/tree/master/10-advanced-rotate-scale)

```
@keyframes pulse {
  0% {}
  50% { transform: rotate(-180deg) scale(5) }
  100% { transform: rotate(-360deg) scale(.2) }
}

.pulse {
  animation: pulse 4s alternate 2;
  ...
}
```


