<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq_eprbwl"/><path class="roz-zlojr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nail" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.roz-zlojr {
  d: path("M9 14V8.5c0-1.75 1.25-3 3-3s3 1.25 3 3V14c0 .75-.5 1.25-1.25 1.25h-3.5C9.5 15.25 9 14.75 9 14m.5 4.75h5");
}

.vq_eprbwl {
  d: path("M6.5 21.5V9C6.5 5 9 2.5 12 2.5S17.5 5 17.5 9v12.5");
}

</style>
