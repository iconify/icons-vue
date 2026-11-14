<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftk27gbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:select-cursor" /></template>
<style>
.ftk27gbnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m3.5 0h3m3.5 0h1.5a2 2 0 0 1 2 2V7m-17 3.5v3m3.5 7H5.5a2 2 0 0 1-2-2V17m7.5-6l9 4l-3.75 1.25L15 20Z");
}

</style>
