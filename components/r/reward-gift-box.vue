<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz-88ob9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reward-gift-box" /></template>
<style>
.uz-88ob9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h17v4.5h-17ZM5 12.5h14V21H5ZM12 8v13m0-13c-1.5-3-5-5-5.25-2.25C6.6 7.25 9 8 12 8m0 0c1.5-3 5-5 5.25-2.25C17.4 7.25 15 8 12 8");
}

</style>
