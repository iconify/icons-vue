<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wacdhdggq"/><path class="ll5-yfikn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reaction-care" /></template>
<style>
.ll5-yfikn {
  d: path("m12 12.25l-3.5-3.5c-1.5-1.5-1.25-4 1-4.25c1.25-.15 2 .65 2.5 1.5c.5-.85 1.25-1.65 2.5-1.5c2.25.25 2.5 2.75 1 4.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wacdhdggq {
  d: path("M3 7v4.5a9 9 0 0 0 18 0V7");
}

</style>
