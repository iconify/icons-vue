<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lg1d9frtf"/><path class="q-jxavo7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:underfloor-heating" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg1d9frtf {
  fill: currentColor;
  d: path("M3.75 8h16.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H3.75A1.25 1.25 0 0 1 2.5 9.25A1.25 1.25 0 0 1 3.75 8");
}

.q-jxavo7l {
  d: path("M9 6q-.75-1 0-2t0-2m6 4q-.75-1 0-2t0-2M2.5 13.5h16.25a2 2 0 0 1 0 4H5.25a2 2 0 0 0 0 4H21.5");
}

</style>
