<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wbucrcioa"/><path class="wc-4ox-yl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:status-complete" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbucrcioa {
  d: path("M21.25 9.5a9.5 9.5 0 1 1-6.75-6.75");
}

.wc-4ox-yl {
  d: path("m7 11l4 4l7.5-7.5");
}

</style>
