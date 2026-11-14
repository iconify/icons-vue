<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y47x86llf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rainfall-heavy" /></template>
<style>
.y47x86llf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13H17a3.5 3.5 0 0 0 .5-7A5.5 5.5 0 0 0 7 6.5a3.25 3.25 0 0 0-.5 6.5ZM9 16l-1.5 4.5M13 16l-1.5 4.5M17 16l-1.5 4.5");
}

</style>
