## Welcome to Quran Meta Project

This project is to help with Quran related meta queries. 

Answering Questions like:

* How many ayahs in given sura (`getAyaCountinSura`)
* Is given aya 
  * a sajdah ayah?
  * beginnning of a juz (`isAyahJuzFirst`)?
  * beginnning of a page? 
* `findJuz` and `findJuzByAyaid`
* `findPage` by surah/aya
* Find next or previous ayah (`nextAyah`/`prevAyah`)
* converts `[surah,aya]` to `ayaId` and vice-verse ( `findSurahByAyaid` and  `findAyaidBySurah`) 

### APi Reference Documentation

See [here](https://quran-center.github.io/quran-meta/docs/globals.html) for API documentation

### Examples
You can find some examples [here](https://quran-center.github.io/quran-meta/examples/) and souce code for them [here](https://github.com/quran-center/quran-meta/tree/master/examples)

### Demo
* [Quran Meta Visualiser](https://codesandbox.io/s/quran-visualiser-p3zjd) - demo app showcasing number of methods from Quran-meta to build interactive visualisations of Quran structure

### Distributions and Downloads

Here you can find the following
* [Source code](https://github.com/quran-center/quran-meta/tree/master/src) in typescript
* [Javascript code](https://github.com/quran-center/quran-meta/tree/master/lib_esnext) autotranspiled from TS as ES Next
* [Javascript code](https://github.com/quran-center/quran-meta/tree/master/lib) autotranspiled from TS as CJS
* [distributions](https://github.com/quran-center/quran-meta/tree/master/dist) of library as 
   *   [UMD](https://quran-center.github.io/quran-meta/dist/quran-meta.js) / [UMD minified](https://quran-center.github.io/quran-meta/dist/quran-meta.min.js) builds can be used directly in the browser via a <script>
   * [CommonJS](https://quran-center.github.io/quran-meta/dist/quran-meta.common.js)  for use with older bundlers like browserify or webpack
   * [ESM](https://quran-center.github.io/quran-meta/dist/quran-meta.esm.js)  for use with modern bundlers like webpack 2 or Rollup
   * [ESM Browser](https://quran-center.github.io/quran-meta/dist/quran-meta.esm.browser.js)/[ESM Browser minified](https://quran-center.github.io/quran-meta/dist/quran-meta.esm.browser.min.js)   for direct imports in modern browsers via <script type="module">