<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mtiwtcckv"/><path class="nlhpocb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sankey-energy" /></template>
<style>
.mtiwtcckv {
  d: path("M21.5 3C14 3 10 6 2.5 6v12c7.5 0 11.5 2.5 19 2.5");
}

.nlhpocb6r {
  d: path("M21.5 8q-6.5.5-9 1.5q2.5 1.5 9 1.5m0 3.5Q16 14.75 13 16q3 1.25 8.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
