<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0ji37ikq"/><path class="vqb1uwd9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-manager" /></template>
<style>
.a0ji37ikq {
  d: path("m3.731 10.4l2.981-3.875A2.63 2.63 0 0 1 8.793 5.5h10.082A2.625 2.625 0 0 1 21.5 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625H8.793a2.63 2.63 0 0 1-2.081-1.025L3.731 13.6a2.625 2.625 0 0 1 0-3.2M7.5 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqb1uwd9p {
  d: path("m13 9l-2 3l2 3m3.5-6l2 3l-2 3");
}

</style>
