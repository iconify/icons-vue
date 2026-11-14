<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkmkbllve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:select-cursor" /></template>
<style>
.gkmkbllve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m3.5 0h3m3.5 0h1.5a2 2 0 0 1 2 2V7m-17 3.5v3m3.5 7H5.5a2 2 0 0 1-2-2V17m11.064-4.416l3.63 1.613a.767.767 0 0 1-.069 1.428l-1.163.388a1.5 1.5 0 0 0-.949.949l-.388 1.163a.767.767 0 0 1-1.428.069l-1.613-3.63a1.5 1.5 0 0 1 1.98-1.98");
}

</style>
