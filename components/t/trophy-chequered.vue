<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k3ua4iazt"/><path class="s-en5xboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy-chequered" /></template>
<style>
.k3ua4iazt {
  d: path("M13.486 11.511q-.322.239-.677.424t-.736.311t-.776.19t-.797.064q-.123 0-.245-.006q-.123-.006-.245-.018t-.244-.03t-.241-.042q-.121-.024-.24-.054t-.236-.065q-.118-.036-.233-.077q-.116-.042-.229-.089q-.114-.047-.225-.099t-.219-.11t-.214-.121t-.207-.132q-.102-.068-.2-.141t-.194-.151q-.095-.078-.186-.16q-.091-.083-.178-.169q-.086-.087-.169-.178q-.082-.091-.16-.186t-.151-.194t-.141-.2q-.069-.102-.132-.207q-.063-.106-.121-.214t-.11-.219t-.099-.225q-.047-.113-.089-.229q-.041-.115-.077-.233q-.035-.117-.065-.236t-.054-.24q-.024-.12-.042-.241q-.018-.122-.03-.244t-.018-.245Q5.5 7.623 5.5 7.5V3h10v4.5q0 .264-.028.527t-.083.521t-.138.509t-.19.492q-.108.241-.241.469q-.134.228-.29.441t-.334.409t-.376.37");
}

.s-en5xboh {
  d: path("M5.5 5H3v1.5A3.5 3.5 0 0 0 6.25 10m9.25-5H18v1.5a3.5 3.5 0 0 1-3.25 3.5m-4.25 2.5V17m2.9 3H7.5v-3h5.9m2.85 4.5V14h5.25v4.5h-5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
