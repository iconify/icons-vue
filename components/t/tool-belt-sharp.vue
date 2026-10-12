<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i39wl2dkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tool-belt-sharp" /></template>
<style>
.i39wl2dkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5h-6.5v3.5h6.5Zm5.5 0h6.5v3.5h-6.5Zm-5.5-1h5.5v5.5h-5.5zM8 12H2.75v1.25M5.5 12v9.25m11.23-9.52a2.5 2.5 0 1 0 3.54 0M18.5 16v5.25");
}

</style>
