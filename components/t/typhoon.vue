<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9e5ib9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:typhoon" /></template>
<style>
.kd9e5ib9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7a7 7 0 0 1 8.5 8m-4.25-.5A7 7 0 0 1 5 17.75m2.75-3.25A7 7 0 0 1 10.5 3.25M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
