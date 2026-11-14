<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6h9wr90l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:variables-panel" /></template>
<style>
.a6h9wr90l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19v17h-19Zm3 4L8 10m0-2.5L5.5 10m5-2.5h2m-2 2.75h2m2.5-1.5h3.5M5.5 14L8 16.5M8 14l-2.5 2.5m5-2.5h2m-2 2.75h2m2.5-1.5h3.5");
}

</style>
