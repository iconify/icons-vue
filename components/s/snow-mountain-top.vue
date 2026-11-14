<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vjtyrzyfe"/><path class="qctfvgbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-mountain-top" /></template>
<style>
.qctfvgbrd {
  d: path("m8.75 9l1.75 2.25l1.5-1.5l1.5 1.5L15.25 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjtyrzyfe {
  d: path("M2.5 20L12 3.5L21.5 20Z");
}

</style>
