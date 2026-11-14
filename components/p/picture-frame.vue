<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pd77s14bg"/><path class="x3r4a_k1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:picture-frame" /></template>
<style>
.pd77s14bg {
  d: path("M3 6.5h18v14H3Zm5 0l4-4l4 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3r4a_k1u {
  d: path("m3 17l5.5-5.5l4 4l3-3L21 18");
}

</style>
