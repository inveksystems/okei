# ОКЕИ - общероссийский классификатор единиц измерений. Поиск по коду ОКЕИ, sql дамп ОКЕИ
-----------

```js
'use strict'

const okei = require('./src/okei.js')

console.log(okei.get('064'))
// { code: '064',
//   name: 'Миллион условных квадратных метров',
//   conventionalNationalView: '10^6 усл. м2',
//   conventionalInternationalView: '',
//   symbolNationalView: 'МЛН УСЛ М2',
//   symbolInternationalView: '' }

console.log(okei.has('064')) // true

console.log(okei.store())
// [ { code: '047',
//     name: 'Морская миля (1852 м)',
//     conventionalNationalView: 'миля',
//     conventionalInternationalView: 'n mile',
//     symbolNationalView: 'МИЛЬ',
//     symbolInternationalView: 'NMI' },
//   { code: '008',
//     name: 'Километр; тысяча метров',
//     conventionalNationalView: 'км; 10^3 м',
//     conventionalInternationalView: 'km',
//     symbolNationalView: 'КМ; ТЫС М',
//     symbolInternationalView: 'KMT' },
//   { code: '005',
//     name: 'Дециметр',
//     conventionalNationalView: 'дм',
//     conventionalInternationalView: 'dm',
//     symbolNationalView: 'ДМ',
//     symbolInternationalView: 'DMT' },
// ...]

```
