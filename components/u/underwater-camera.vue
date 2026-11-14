<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="joh53socq"/><path class="a6assn7kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:underwater-camera" /></template>
<style>
.a6assn7kf {
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.joh53socq {
  d: path("M8.875 6h6.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 15.125 18h-6.25A4.375 4.375 0 0 1 4.5 13.625v-3.25A4.375 4.375 0 0 1 8.875 6M4.5 8.5h-2v7h2m15-7h2v7h-2");
}

</style>
