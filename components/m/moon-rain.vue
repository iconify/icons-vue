<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4fwfebve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:moon-rain" /></template>
<style>
.l4fwfebve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 9.5a6 6 0 1 1-7-7a7 7 0 0 0 7 7Zm-10 8l-1 4m5-4l-1 4m5-4l-1 4");
}

</style>
