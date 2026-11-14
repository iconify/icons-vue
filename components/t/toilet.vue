<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8-fllbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toilet" /></template>
<style>
.x8-fllbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5H11V12H6.5Zm0 8.5H18c0 3.25-1.75 5.25-4 5.75v2.75H9.5v-3c-1.75-1-3-3-3-5.5Z");
}

</style>
