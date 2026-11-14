<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ysxclmd-n"/><path class="ryb47vbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:newspaper-rolled" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ryb47vbyp {
  d: path("M6 6h11.5a2.5 6 0 0 1 0 12H6m6.5-12v12");
}

.ysxclmd-n {
  d: path("M3.5 12a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0");
}

</style>
