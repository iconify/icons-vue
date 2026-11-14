<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfw-r1bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortar-pestle-lab" /></template>
<style>
.rfw-r1bzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5h17c0 5.5-3.5 9-8.5 9s-8.5-3.5-8.5-9Zm6.75 0V4.25a1.75 1.75 0 0 1 3.5 0v7.25");
}

</style>
