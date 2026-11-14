<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqbsfob2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-temperature" /></template>
<style>
.mqbsfob2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 16h10l-1 5.5H5Zm5 0v-6m0 3c-3 0-5.5-2-5.5-5.5C7 7.5 9 10 9 13Zm0-3c0-3.5 2.5-6.5 6-6.5C15 7 12.5 10 9 10Zm8.75 7v-2.5a1.25 1.25 0 0 1 2.5 0V17a2.5 2.5 0 1 1-2.5 0Z");
}

</style>
