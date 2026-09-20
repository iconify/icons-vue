<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="by6r7ba-o"/><path class="mcubrkb2y"/><path class="gyhtx7usr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mobile-banking-duotone-thin" /></template>
<style>
.by6r7ba-o {
  fill: currentColor;
  d: path("M10 12h4v6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gyhtx7usr {
  d: path("M10 12h4v6h-4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

</style>
