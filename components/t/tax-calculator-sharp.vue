<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zez-f6umd"/><path class="kpgldhbxi"/><path class="id2a4xb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tax-calculator-sharp" /></template>
<style>
.id2a4xb9m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 17.25h7.5");
}

.kpgldhbxi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 7.75h.01m5.49 5.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zez-f6umd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v18.5H4.75zm4.5 10.5l5.5-5.5");
}

</style>
