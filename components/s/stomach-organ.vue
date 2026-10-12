<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yvcvn_bjn"/><path class="oehp4oubc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stomach-organ" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oehp4oubc {
  d: path("M3.75 17.25c-1 1.25-.75 4 1.5 4h2.5m7-11.75q.75-.75 1.5 0c.75.75 1 .5 1.5 0m-1.75 3q.75-.75 1.5 0c.75.75 1 .5 1.5 0m-4 3.25q.75-.75 1.5 0c.75.75 1 .5 1.5 0");
}

.yvcvn_bjn {
  d: path("M8 2.75h2.5V6c1-.5 2.25-.75 3.5-.75c3.75 0 6.25 3 6.25 7c0 4.75-3.75 8-8.25 8c-2 0-3.75-.75-4.75-1.75H5.5a1.75 1.75 0 0 1 0-3.5h1.75c1 .75 2.25 1.25 3.5 1.25c2.25 0 3.75-1.5 3.75-3.75c0-2-1.25-3.25-3-3.25c-1.25 0-2 .5-2.75 1L8 7.75Z");
}

</style>
