<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g62sjn4zc"/><path class="vwk13s-_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rewards-chest" /></template>
<style>
.g62sjn4zc {
  d: path("M3 10h18v10.5H3Zm0 0a9 6 0 0 1 18 0M3 14.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vwk13s-_u {
  d: path("M10.5 13h3v4.5h-3Z");
}

</style>
