# DOM-tehtävät

Lataa tämä repo zip-pakettina klikkaamalla 'clone or download' -painiketta.

### Tehtävä A, CSS
1. Editoi CSS-koodia opettajan ohjeiden mukaisesti.
   
### Tehtävä B, [JavaScript HTML DOM](https://www.w3schools.com/js/js_htmldom.asp)
1. Tee uusi tiedosto task-b.html
1. Kopioi index.html tiedoston sisältö ja liitä se task-b.html tiedostoon
1. Vaihda `<script>` elementin src-attribuutin arvoksi main-b.js
1. Lisää tiedoston js/main-b.js `<main>` elementtiin toinen `<article>` elementti:
   * Uusi `<article>` elementti sisältää samat elementit kuin valmiina oleva `<article>` elementti 
   * Valitse `<main>` elementti käyttäen [DOM-metodeja](https://www.w3schools.com/js/js_htmldom_elements.asp)
   * Käytä [innerHTML](https://www.w3schools.com/js/js_htmldom_html.asp) ominaisuutta lisätessäsi `<article>` elementin `<main>` elementtiin.
   * Huomaa, että sinun on käytettävä `+=` operaattoria lisäyksessä.
   * Jos haluat sisällyttää HTML:än useamman rivin pituisen merkkijonon, käytä + operaattoria tai tee [template string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
   
### Tehtävä C, [JavaScript HTML DOM Elements](https://www.w3schools.com/js/js_htmldom_nodes.asp)
1. Tee uusi tiedosto task-c.html
1. Kopioi tiedoston index.html sisältö ja liitä se tiedostoon task-c.html
1. Vaihda `<script>`-elementin src-attribuutin arvoksi main-c.js
1. Lisää uusi `<article>`-elementti `<main>`-elementtiin:
   * Uusi `<article>` elementti sisältää samat elementit kuin valmiina oleva `<article>` elementti 
   * Valitse `<main>` elementti käyttäen [DOM-metodeja](https://www.w3schools.com/js/js_htmldom_elements.asp)
   * Käytä DOM metodeja (createElement, appendChild) lisätessäsi `<article>` elementin `<main>` elementtiin.

### Tehtävä D, HTML sisällön lisääminen taulukosta [iteroimalla](https://www.w3schools.com/js/js_loop_for.asp)
1. Tee uusi tiedosto task-d.html
1. Kopioi tiedoston index.html sisältö ja liitä se tiedostoon task-d.html
1. Vaihda `<script>`-elementin src-attribuutin arvoksi main-d.js
1. Poista `<article>` elementti `<main>` elementistä.
1. Lisää `<article>` elementti `<main>` elementtiin iteroimalla picArray toistorakennetta käyttäen (main-d.js).
   * Uusi `<article>` elementti sisältää samat elementit kuin valmiina oleva `<article>` elementti
   * Valitse `<main>`elementti DOM-metodeja käyttäen
   * Käytä DOM-metodeja (createElement, appendChild) tai innerHTML-ominaisuutta lisätäksesi `<article>` elementin `<main>`elementtiin.
      * Lisää otsikko `<h2>` elementtiin ja `<img>` elementin alt-attribuuttiin
      * Lisää seloste `<caption>` elementtiin
      * Lisää tiedostopolku `<img>` elementin src-attribuuttiin
      * Lisää kuvaus `<p>` elementtiin
