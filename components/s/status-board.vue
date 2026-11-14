<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="hd9rnobea"/><path class="xez9qwptf"/><path class="b499h2bkp"/><path class="cctdhsici"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-board" /></template>
<style>
.b499h2bkp {
  fill: currentColor;
  d: path("M5.5 16.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.cctdhsici {
  d: path("M10 7.5h7.5M10 12h6m-6 4.5h7.5");
}

.hd9rnobea {
  fill: currentColor;
  d: path("M5.5 7.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xez9qwptf {
  d: path("M5.5 12A1.25 1.25 0 1 0 8 12a1.25 1.25 0 1 0-2.5 0Z");
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

</style>
