<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osory8bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:situation-map" /></template>
<style>
.osory8bev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 5.5l6-2l7 2l6-2v15l-6 2l-7-2l-6 2Zm3 10l2-1.25M10 12.5l2-1.25m4.5-2.75h.01");
}

</style>
