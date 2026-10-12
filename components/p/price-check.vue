<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w1w8zudbu"/><circle class="i1t46rt8z"/><path class="t8u-hjb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:price-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1t46rt8z {
  cx: 12px;
  cy: 7.75px;
  r: 1.5px;
}

.t8u-hjb1k {
  d: path("M9.25 12.75h5.5m-5.5 3.5h3.5");
}

.w1w8zudbu {
  d: path("m6.85 6.6l4.4-3.6a1.2 1.2 0 0 1 1.5 0l4.4 3.6a2 2 0 0 1 .6 1.43v11.22a2 2 0 0 1-2 2h-7.5a2 2 0 0 1-2-2V8.03a2 2 0 0 1 .6-1.43");
}

</style>
