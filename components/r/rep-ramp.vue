<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bostc9b0v"/><path class="m5nmg8bna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rep-ramp" /></template>
<style>
.bostc9b0v {
  d: path("M11.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c2.083 0 3.926.541 5.264 1.474M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8 13.5L17 18l1.5 1.5l3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5nmg8bna {
  d: path("M19.25 16.5h2.25v2.25");
}

</style>
