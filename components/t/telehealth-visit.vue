<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gd-s7abat"/><path class="g8f850bqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:telehealth-visit" /></template>
<style>
.g8f850bqi {
  d: path("M7 2.5V7c0 1.75 1.25 3 2.75 3s2.75-1.25 2.75-3V2.5M9.75 10v1.5c0 1.25 1 2 2.25 2s2-1 2-1.75m0-.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.gd-s7abat {
  d: path("M6.125 5h11.75A2.625 2.625 0 0 1 20.5 7.625v5.75A2.625 2.625 0 0 1 17.875 16H6.125A2.625 2.625 0 0 1 3.5 13.375v-5.75A2.625 2.625 0 0 1 6.125 5M2 19h20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
