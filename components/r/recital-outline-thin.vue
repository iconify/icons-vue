<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sjwck004e"/><path class="bo51iypxr"/><path class="uw8-z-bjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recital-outline-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sjwck004e {
  d: path("M10.5 2 6 6.5h11.5L13 2Z");
}

.uw8-z-bjv {
  d: path("M7 20a5 5 0 0 1 10 0");
}

</style>
