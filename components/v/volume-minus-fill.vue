<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y9yf7qbhl"/><path class="q-9nypbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-minus-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-9nypbtt {
  d: path("M16 12H22");
}

.y9yf7qbhl {
  fill: currentColor;
  d: path("M1 10C1 8.895431 1.895431 8 3 8L5.477658 8L8.3585 3.861189C9.477163 2.254043 12 3.045621 12 5.003765L12 18.996235C12 20.954379 9.477163 21.745957 8.3585 20.138811L5.477658 16L3 16C1.895431 16 1 15.104569 1 14Z");
  stroke: none;
}

</style>
