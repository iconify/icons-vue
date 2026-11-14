<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="os3_2y-hp"/><path class="x3r4a_k1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:picture-frame" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.os3_2y-hp {
  d: path("M5.625 6.5h12.75A2.625 2.625 0 0 1 21 9.125v8.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 17.875v-8.75A2.625 2.625 0 0 1 5.625 6.5M8 6.5l4-4l4 4");
}

.x3r4a_k1u {
  d: path("m3 17l5.5-5.5l4 4l3-3L21 18");
}

</style>
