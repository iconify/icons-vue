<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uove92bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:music-room" /></template>
<style>
.uove92bke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12V4A1.5 1.5 0 0 1 6 2.5h12A1.5 1.5 0 0 1 19.5 4v8m-17 0h19v4.5h-19Zm2 4.5v5m15-5v5M6.5 12v2.25m3-2.25v2.25m5-2.25v2.25m3-2.25v2.25m-7 6.25h.01m2.99 0h.01");
}

</style>
