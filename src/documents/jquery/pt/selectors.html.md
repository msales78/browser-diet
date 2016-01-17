---
order: 9
title: Seletores
---

Seletores são uma das questões mais importantes no uso do jQuery. Há muitas maneiras diferentes de selecionar um elemento no DOM, mas isso não significa que eles tem o mesmo desempenho, você pode selecionar um elemento usando Classes, IDs ou outros métodos como `find()`, `children()`.

Entre todos eles, o mais rápido é selecionar um ID, pois trata-se de uma operação nativa no DOM:

```js
$("#foo");
```

*[> Resultados no JSPerf](http://jsperf.com/browser-diet-jquery-selectors)*
