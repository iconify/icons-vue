<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="lqt1g5bdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terminal-play" /></template>
<style>
.lqt1g5bdf {
  d: path("m6 7l2.5 2.5L6 12m6-2l6.5 4l-6.5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

</style>
