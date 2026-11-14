<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iizzxacfc"/><path class="cycis-bjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mask-privacy" /></template>
<style>
.cycis-bjn {
  d: path("M5.25 11a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0m9 0a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iizzxacfc {
  d: path("M2.5 9c0-1.5 1-2.5 2.5-2.5h14c1.5 0 2.5 1 2.5 2.5v2c0 3.5-2.5 5.5-5.5 5.5c-2 0-3-1.5-4-2.5c-1 1-2 2.5-4 2.5c-3 0-5.5-2-5.5-5.5Z");
}

</style>
