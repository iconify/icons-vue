<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl9wntqlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowy-tree" /></template>
<style>
.tl9wntqlj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l5.5 7h-2l4.5 7H4l4.5-7h-2Zm0 14v3.75M5 21.5q7-2.5 14 0M5.5 4h.01M19 5.5h.01m-15.51 6h.01");
}

</style>
