<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3lh54sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tracking-camera" /></template>
<style>
.oj3lh54sm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h13v7H3ZM16 4l3.5-1v6L16 8M8.5 9.5v5H3M15 17v-2h2m3 0h2v2m0 3v2h-2m-3 0h-2v-2");
}

</style>
