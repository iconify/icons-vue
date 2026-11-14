<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbqwyt1yv"/><path class="e-7ablbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slideshow" /></template>
<style>
.e-7ablbwk {
  d: path("m10 6.5l4.5 2.75L10 12Zm2 9v3M7.5 21l4.5-2.5l4.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbqwyt1yv {
  d: path("M2.5 3h19v12.5h-19Z");
}

</style>
