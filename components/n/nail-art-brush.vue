<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x5tir4bla"/><path class="nahqgbibw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nail-art-brush" /></template>
<style>
.nahqgbibw {
  d: path("M10.646 9.232L17.01 4.99l-4.242 6.364ZM18.5 8.5s2 2.5 2 3.5a2 2 0 0 1-4 0c0-1 2-3.5 2-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5tir4bla {
  d: path("m10.646 9.232l2.122 2.122l-7.778 7.778l-2.122-2.122Z");
}

</style>
