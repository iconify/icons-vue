<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7jtygb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scuba-mask" /></template>
<style>
.r7jtygb4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9a3 3 0 0 1 3-3h11a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-3L12 13.5L9.5 16h-3a3 3 0 0 1-3-3ZM12 6v4.5");
}

</style>
