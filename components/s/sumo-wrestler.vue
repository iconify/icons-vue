<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-iybacyv"/><path class="qx6uwbv5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sumo-wrestler" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-iybacyv {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.25 9a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M3 8.5l5.25 3m7.5 0l5.25-3");
}

.qx6uwbv5n {
  d: path("M9 16.5L5 18l-.5 3.5m10.5-5l4 1.5l.5 3.5");
}

</style>
