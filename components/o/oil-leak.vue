<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_1elfrif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-leak" /></template>
<style>
.h_1elfrif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9h9.5v8a1.5 1.5 0 0 1-1.5 1.5h-6.5A1.5 1.5 0 0 1 9 17Zm9.5 1.5H20a1.5 1.5 0 0 1 1.5 1.5v2.5A1.5 1.5 0 0 1 20 16h-1.5M12 9V6.5h3.5V9M9 11L3.5 6m.25 4S2 12.75 2 14a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-4-1.75-4Z");
}

</style>
