<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eohvp-yvr"/><path class="dw0f580hj"/><path class="x4_r5xwup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ranch-house" /></template>
<style>
.dw0f580hj {
  d: path("M4.5 10.5V20h15v-9.5M2.5 20h19");
}

.eohvp-yvr {
  d: path("M2.5 11.5L12 6l9.5 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4_r5xwup {
  d: path("M7.25 20v-5.5H10V20m2.75-6.5H17v3h-4.25Z");
}

</style>
