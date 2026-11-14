<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s57bicdra"/><path class="weq1prtgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soda-siphon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s57bicdra {
  d: path("M10 7v3.5c-3.5 1-5.5 3-5.5 5.75c0 3.5 3 5.25 7.5 5.25s7.5-1.75 7.5-5.25c0-2.75-2-4.75-5.5-5.75V7m-3.75-4h3.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13.75 7h-3.5A1.75 1.75 0 0 1 8.5 5.25v-.5A1.75 1.75 0 0 1 10.25 3");
}

.weq1prtgq {
  d: path("M8.5 5h-3l-1 2.5m11-4l4.5 3");
}

</style>
