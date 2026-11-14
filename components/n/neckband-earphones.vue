<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fja47rb1a"/><path class="ym9z0b8lf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:neckband-earphones" /></template>
<style>
.fja47rb1a {
  d: path("M5.5 6v6a6.5 6.5 0 0 0 13 0V6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ym9z0b8lf {
  d: path("M5.5 2.5za2 2 0 0 1 2 2V5a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-.5a2 2 0 0 1 2-2m13 0za2 2 0 0 1 2 2V5a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-.5a2 2 0 0 1 2-2");
}

</style>
