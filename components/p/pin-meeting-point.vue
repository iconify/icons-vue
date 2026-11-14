<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgewl8bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-meeting-point" /></template>
<style>
.lgewl8bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM8 20c0-3.5 1.75-5.5 4-5.5s4 2 4 5.5M2.75 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm14.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 20c0-2.5 1-4 2.75-4m16.25 4c0-2.5-1-4-2.75-4");
}

</style>
