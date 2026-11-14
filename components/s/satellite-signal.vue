<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo-wfbbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-signal" /></template>
<style>
.zo-wfbbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8.75a9 9 0 0 0 11.5 11.5ZM9.5 14.5l3.75-3.75m0-4a4 4 0 0 1 4 4m-4-7.5a7.5 7.5 0 0 1 7.5 7.5");
}

</style>
