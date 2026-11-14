<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl5jpwlqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mushroom-anatomy" /></template>
<style>
.wl5jpwlqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a9 8 0 0 1 18 0Zm6 0l-.5 8.5A1.5 1.5 0 0 0 10 21h4a1.5 1.5 0 0 0 1.5-1.5L15 11m-3-8v18");
}

</style>
