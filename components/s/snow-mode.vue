<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jx6u2vbem"/><path class="cimg-_mvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-mode" /></template>
<style>
.cimg-_mvy {
  d: path("M10.75 7.75L12 9l1.25-1.25m-2.5 8.5L12 15l1.25 1.25m3.056-3.208l-1.708.458l.458 1.708M8.944 8.792l.458 1.708l-1.708.458m1.25 4.25l.458-1.708l-1.708-.458m8.612-2.084l-1.708-.458l.458-1.708");
}

.jx6u2vbem {
  d: path("M5 3.5h14A1.5 1.5 0 0 1 20.5 5v14a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 19V5A1.5 1.5 0 0 1 5 3.5ZM12 7v10m4.33-7.5l-8.66 5m8.66 0l-8.66-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
