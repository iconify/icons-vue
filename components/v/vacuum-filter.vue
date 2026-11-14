<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8fgk_-ug"/><path class="luijxcbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vacuum-filter" /></template>
<style>
.l8fgk_-ug {
  d: path("M5 4v15.5a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4");
}

.luijxcbwv {
  d: path("M8.5 2.5h7v16h-7Zm0 4.5h7m-7 3.5h7m-7 3.5h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
