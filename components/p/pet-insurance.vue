<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvxz5reft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-insurance" /></template>
<style>
.kvxz5reft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10a9 7.5 0 0 1 18 0q-3-1.5-6 0q-3-1.5-6 0q-3-1.5-6 0Zm4.5 3l2.5 2.25h4L16.5 13v4.5a4.5 4 0 0 1-9 0Zm2.75 4.25h.01m3.49 0h.01");
}

</style>
