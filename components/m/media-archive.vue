<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yabjiab6i"/><path class="oo6jldb3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:media-archive" /></template>
<style>
.oo6jldb3d {
  d: path("m10 11.25l5.5 3l-5.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yabjiab6i {
  d: path("M3 4h18v4.5H3Zm1.5 4.5v10A1.5 1.5 0 0 0 6 20h12a1.5 1.5 0 0 0 1.5-1.5v-10");
}

</style>
