<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3uoymbcj"/><circle class="nsu12ob8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-router" /></template>
<style>
.f3uoymbcj {
  d: path("M2.75 12H8m6.25 0h7m-8-2.5L16 6h5.25m-8 8.5L16 18h5.25M19.5 4.25L21.25 6L19.5 7.75m0 2.5L21.25 12l-1.75 1.75m0 2.5L21.25 18l-1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nsu12ob8g {
  cx: 11.25px;
  cy: 12px;
  r: 3px;
}

</style>
