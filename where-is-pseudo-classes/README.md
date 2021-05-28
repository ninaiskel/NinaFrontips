# Pseudo classes :Where() & :is()

`:Where()` & `:is()` son unas pseudo classes de CSS que nos permiten escribir selectores compuestos de manera mas concisa, para evitar la repetición.

Ambos son funciones que toman una serie de argumentos de selectores como(ids, classes, tags etc) para luego pasarles el estilo que se desee.

#

![](demo/where-is.gif)

#

<!-- [youtube demo]() -->

## Syntax

```
:where(.class, p, ...){}
:is(a, .class, h4 ...){}
```

## More info

- [Pseudo Class Selectors](https://css-tricks.com/pseudo-class-selectors/)
- [The pseudo-select :is()](https://css-tricks.com/almanac/selectors/i/is/)
