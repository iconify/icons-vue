<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="idd13m22d"/><path class="ow1n1tb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slide-sample" /></template>
<style>
.idd13m22d {
  d: path("M2.5 8h19v8h-19Z");
}

.ow1n1tb7t {
  d: path("M5.5 9.75H10v4.5H5.5ZM7.75 12h.01M15 8v8m1.75-5.5h3m-3 3h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
