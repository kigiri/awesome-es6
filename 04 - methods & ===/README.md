#  [`Methods`](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Index_des_m%C3%A9thodes) & [`===`](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Op%C3%A9rateurs/Op%C3%A9rateurs_de_comparaison)

Tout ceci n'est pas forcément présent depuis ES6, mais n'hésitez pas à jetter un coup d'oeil :
- [js-methods](https://github.com/nan-ci/js-methods)

Ok, alors si toi aussi tu t'es déjà demandé *pourquoi est-ce qu'il y a un `===` en JS ?* 

Il existe deux opérateurs de comparaison :

- comparaison strict (```===```)
- comparaison d'égalité faible (```==```)

Le ```===``` ne renvoie ```true``` que si les deux opérandes sont du même type.

```js
3 === 3   // true
3 === '3' // false
3 !== '3' // true

0 === false // false
0 === null // false
0 === undefined // false
null === undefined // false
```

Le ```==``` convertie les deux opérandes s'ils ne sont pas du même type.

```js
3 == 3   // true
3 == '3' // true
3 != '3' // false

0 == false // true
0 == null // false
0 == undefined // false
null == undefined // true
```

## Pour approfondir :

- [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators)
- [Stack Overflow](https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons/)
