<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elvkp-b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-sampling-point" /></template>
<style>
.elvkp-b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h11a4 4 0 0 1 4 4V11h-4V9.5h-11m5.5-4v-3m-2.5 0h5m3 11.5v5.5a2 2 0 0 0 4 0V14m-5 0h6");
}

</style>
