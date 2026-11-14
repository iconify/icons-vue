<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0559abef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seasonal-display" /></template>
<style>
.s0559abef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16h17v5.5h-17ZM12 2.5l4.5 6h-2.25l3.25 5h-11l3.25-5H7.5Zm0 11V16m-5.5 2.75h11");
}

</style>
