<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8l8dbb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vacant-land" /></template>
<style>
.r8l8dbb5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5V3h3.5m11 0H21v3.5m0 11V21h-3.5m-11 0H3v-3.5M10 3h4m7 7v4m-7 7h-4m-7-7v-4m5.5 6h7M10 16c-.5-2.5-1.5-3.5-3-4.25M12 16c0-2.5.5-4.5 1-6.5m1 6.5c.5-2 1.5-3 3-3.5");
}

</style>
