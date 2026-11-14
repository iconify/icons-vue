<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="exfiwjbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sos-button" /></template>
<style>
.exfiwjbhj {
  d: path("M8.25 10c0-.75-.5-1.25-1.25-1.25s-1.25.5-1.25 1.25c0 1.75 2.5 1.75 2.5 3.75c0 .75-.5 1.5-1.25 1.5s-1.25-.75-1.25-1.5M10.5 12a1.5 3.25 0 1 0 3 0a1.5 3.25 0 1 0-3 0Zm7.75-2c0-.75-.5-1.25-1.25-1.25s-1.25.5-1.25 1.25c0 1.75 2.5 1.75 2.5 3.75c0 .75-.5 1.5-1.25 1.5s-1.25-.75-1.25-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
