<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf7x4uilo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microgreens-tray" /></template>
<style>
.rf7x4uilo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h19l-1 4.5h-17Zm9.5 0V7m0 0q-.75-2.75-3.5-2.5Q9.25 7.25 12 7Zm0 0q.75-2.75 3.5-2.5Q14.75 7.25 12 7Zm-6 7.5v-4m0 0q-.75-2.25-3-2q.75 2.25 3 2Zm0 0q.75-2.25 3-2q-.75 2.25-3 2Zm12 4v-4m0 0q-.75-2.25-3-2q.75 2.25 3 2Zm0 0q.75-2.25 3-2q-.75 2.25-3 2Z");
}

</style>
