<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmwdq6bhb"/><path class="r3fquycoq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmwdq6bhb {
  d: path("M5.518 13.5h4.964a1.75 1.75 0 0 1 1.733 1.997l-.5 3.5A1.75 1.75 0 0 1 9.982 20.5H6.018a1.75 1.75 0 0 1-1.733-1.503l-.5-3.5A1.75 1.75 0 0 1 5.518 13.5");
}

.r3fquycoq {
  d: path("M8 13.5v-5c-.25-3-2.25-5-5.25-5c0 3 2.25 5 5.25 5C8.25 5.25 10.25 3 13.25 3c0 3-2 5.5-5.25 5.5m7.25 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
