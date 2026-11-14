<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzaoxfbmk"/><path class="zumr_nj6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wedding-arch" /></template>
<style>
.bzaoxfbmk {
  d: path("M5 21.5V11a7 7 0 0 1 .5-2.5m2-2.75a7 7 0 0 1 2.75-1.5m3.5 0a7 7 0 0 1 2.75 1.5m2 2.75A7 7 0 0 1 19 11v10.5M10.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zumr_nj6g {
  d: path("M4.5 7A1.75 1.75 0 1 0 8 7a1.75 1.75 0 1 0-3.5 0M16 7a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 16 7");
}

</style>
