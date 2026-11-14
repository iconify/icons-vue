<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mogwmh9mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouthwash" /></template>
<style>
.mogwmh9mf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19.5V12a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v7.5a1.5 1.5 0 0 1-1.5 1.5h-6A1.5 1.5 0 0 1 5 19.5Zm1.5-16h6V9h-6ZM16.75 7c2.75 2 3.75 5 2.25 8.5m1.25 3.5h.01");
}

</style>
