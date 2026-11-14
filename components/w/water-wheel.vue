<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jqqdk0m7p"/><path class="o1xyz2bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-wheel" /></template>
<style>
.jqqdk0m7p {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.o1xyz2bkt {
  d: path("M10 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h5m-9 0H5m8 1.75l2.5 4.25M11 7.75L8.5 3.5m2.5 7.75L8.5 15.5M13 7.75l2.5-4.25M3 20.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
