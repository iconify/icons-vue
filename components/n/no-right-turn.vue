<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjgxau-ai"/><path class="wvokt6bxl"/><path class="o7vhhzbjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-right-turn" /></template>
<style>
.fjgxau-ai {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0m3-6.75l13.5 13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7vhhzbjl {
  d: path("M14.5 6.5L17 9l-2.5 2.5");
}

.wvokt6bxl {
  d: path("M9.5 17.5v-6A2.5 2.5 0 0 1 12 9h5");
}

</style>
