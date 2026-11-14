<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwc3k5b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-playlist" /></template>
<style>
.dwc3k5b0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5h17m-17 5h17m-17 5H10m6 2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.5-3a4.25 4.25 0 0 0 0 6m6-6a4.25 4.25 0 0 1 0 6");
}

</style>
