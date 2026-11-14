<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ca59bbccv"/><path class="zst2ncc6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:memoir" /></template>
<style>
.ca59bbccv {
  d: path("M5 4.5a2 2 0 0 1 2-2h12v19H7a2 2 0 0 1-2-2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zst2ncc6a {
  d: path("M5 19.5A1.5 1.5 0 0 1 6.5 18H19M10.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.5 8a3.25 3.25 0 0 1 6.5 0");
}

</style>
