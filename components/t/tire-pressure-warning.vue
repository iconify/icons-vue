<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am5g6kbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tire-pressure-warning" /></template>
<style>
.am5g6kbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.5c-2 2.25-2.5 5-2.5 7.5c0 3.25 1.5 5.75 3.5 6.5h10c2-.75 3.5-3.25 3.5-6.5c0-2.5-.5-5.25-2.5-7.5m-6 3v5m0 2.75h.01m-4.51 6h.01m4.49 0h.01m4.49 0h.01");
}

</style>
