<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnz75qgiu"/><path class="wb0meebxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-scanner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnz75qgiu {
  d: path("M13.5 2.5H18A3.5 3.5 0 0 1 21.5 6v3a3.5 3.5 0 0 1-3.5 3.5h-4.5A3.5 3.5 0 0 1 10 9V6a3.5 3.5 0 0 1 3.5-3.5m2.25 10V19m-2.5 0h5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-5A1.25 1.25 0 0 1 12 20.25A1.25 1.25 0 0 1 13.25 19");
}

.wb0meebxj {
  d: path("M14.25 5h2.5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-2.5a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5M8 5L2.5 3.5m5.5 4H2.5M8 10l-5.5 1.5");
}

</style>
