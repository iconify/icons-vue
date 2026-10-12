<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s7kq_t5cb"/><path class="c2u4o_y6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rna-sharp" /></template>
<style>
.c2u4o_y6l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.53 13.5h.01M9.23 16h.01m5.54 1.5h.01m3.69 2.5h.01");
}

.s7kq_t5cb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5q4.63-5 9.25 0t9.25 0M5.53 6.4V12m3.7-5.6v8.1m5.55-3.9V16m3.7-5.4v7.9");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
