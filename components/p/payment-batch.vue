<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frmyt1bsi"/><path class="c003hd9-z"/><path class="dyl18hg0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payment-batch" /></template>
<style>
.c003hd9-z {
  d: path("M5.25 10V7.25h13V18H15.5");
}

.dyl18hg0j {
  d: path("M8 7.25V4.5h13v10.75h-2.75M5.5 15.5h7M10 13l2.5 2.5L10 18");
}

.frmyt1bsi {
  d: path("M5.125 10h7.75a2.625 2.625 0 0 1 2.625 2.625v5.75A2.625 2.625 0 0 1 12.875 21h-7.75A2.625 2.625 0 0 1 2.5 18.375v-5.75A2.625 2.625 0 0 1 5.125 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
