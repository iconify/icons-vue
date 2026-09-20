<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uhs9iwb8j"/><path class="bo51iypxr"/><path class="v-t99u-wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rag-pipeline-outline-thin" /></template>
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

.uhs9iwb8j {
  d: path("M2 10a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.v-t99u-wl {
  d: path("M15.5 10a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

</style>
