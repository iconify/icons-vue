<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ngrjsibnl"/><path class="wxpc2tlbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shuffle-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngrjsibnl {
  d: path("M4 16.5h2.5c1.326 0 2.541-.988 3.72-2.31m3.56-4.38c1.179-1.322 2.394-2.31 3.72-2.31H20");
}

.wxpc2tlbf {
  d: path("m17 4.5l3 3l-3 3m-13.5-7l17 17");
}

</style>
