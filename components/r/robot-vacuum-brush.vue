<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bp7wkccig"/><path class="bix35ybqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robot-vacuum-brush" /></template>
<style>
.bix35ybqr {
  d: path("M3 8v3a9 3.5 0 0 0 18 0V8M5 17.25h14v3H5Z");
}

.bp7wkccig {
  d: path("M3 8a9 3.5 0 1 0 18 0A9 3.5 0 1 0 3 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
