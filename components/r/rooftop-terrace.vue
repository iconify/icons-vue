<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgu8ibrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rooftop-terrace" /></template>
<style>
.ivgu8ibrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14h16v7.5H4Zm-1.5 0h19m-12-3.5h5l-.75 3.5h-3.5Zm2.5-2v2m-4-2a2 2 0 0 1 1-3a3 3 0 0 1 6 0a2 2 0 0 1 1 3Zm-1 8.25h.01m4.99 0h.01m4.99 0h.01M7 19.25h.01m4.99 0h.01m4.99 0h.01");
}

</style>
