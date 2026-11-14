<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an0bebczi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reader-count" /></template>
<style>
.an0bebczi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.163 20.5H3.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c.889 0 1.702.126 2.421.379M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM16 4.5a3.5 3.5 0 0 1 .906 6.881m-.656 2.869l-.75 7m4.5-7l-.75 7m-5-4.75h7M14 19.25h7");
}

</style>
