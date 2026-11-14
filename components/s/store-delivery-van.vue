<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1jr-o3li"/><path class="g59r9obmw"/><path class="flqekybdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-delivery-van" /></template>
<style>
.flqekybdu {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.g59r9obmw {
  d: path("M13.5 9h4l4 4v4h-19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1jr-o3li {
  d: path("M2.5 17V7A1.5 1.5 0 0 1 4 5.5h9.5V17");
}

</style>
