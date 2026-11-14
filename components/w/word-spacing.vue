<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apdmb8xlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:word-spacing" /></template>
<style>
.apdmb8xlo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h6.5v6.5H3Zm11.5 0H21v6.5h-6.5Zm-10 13h15m-13-2l-2 2l2 2m11-4l2 2l-2 2");
}

</style>
