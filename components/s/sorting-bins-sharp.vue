<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fxftsrrwu"/><path class="qilery-5w"/><path class="l0f1hubau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sorting-bins-sharp" /></template>
<style>
.fxftsrrwu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.25h6.75l-.06 1l-.63 10l-.06 1H3.5l-.06-1l-.63-10l-.06-1zm10.75 0h6.75l-.06 1l-.63 10l-.06 1h-6.25l-.06-1l-.63-10l-.06-1zm-11.75-3h7.75m-5.25 0v-2.5H8v2.5m5.5 0h7.75m-5.25 0v-2.5h2.75v2.5");
}

.l0f1hubau {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.62 13.69l1.14 2.12l.24.44h-3.25l.24-.44l1.15-2.12l.24-.44z");
}

.qilery-5w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.63 15h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
