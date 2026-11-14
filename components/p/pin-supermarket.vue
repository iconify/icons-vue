<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oi-b85dvg"/><path class="a5e7nsgjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-supermarket" /></template>
<style>
.a5e7nsgjq {
  d: path("M10 3h1a1.5 1.5 0 0 1 1.5 1.5V6A1.5 1.5 0 0 1 11 7.5h-1A1.5 1.5 0 0 1 8.5 6V4.5A1.5 1.5 0 0 1 10 3m5.25 4.5a2.25 2.25 0 0 1 4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oi-b85dvg {
  d: path("M2.5 4h2l3 11.5H18l2.5-8h-15m2 12.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
