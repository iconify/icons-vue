<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jxs_2zb1y"/><path class="bipjcgbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-record" /></template>
<style>
.bipjcgbra {
  fill: currentColor;
  d: path("M7 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.jxs_2zb1y {
  d: path("M2.5 6h13v12h-13Zm13 4l6-3v10l-6-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
