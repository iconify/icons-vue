<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzzcvlbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mining-check" /></template>
<style>
.nzzcvlbrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3q8.396 1.482 9.962 9.793M16.75 6.25L6.5 16.5m-4 4.5L5 16.5h4l3 4.5Zm12.25-3l2 2L21 15.75");
}

</style>
