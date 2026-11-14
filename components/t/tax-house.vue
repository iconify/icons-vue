<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l087an1gy"/><path class="gllpxrb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tax-house" /></template>
<style>
.gllpxrb_n {
  d: path("M5 9v11a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9m-9.75 9l5.5-6.25m-5 1h.01M14.25 17h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l087an1gy {
  d: path("M2.5 11L12 3l9.5 8");
}

</style>
