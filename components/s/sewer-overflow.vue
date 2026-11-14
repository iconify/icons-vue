<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwa3x_n_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sewer-overflow" /></template>
<style>
.bwa3x_n_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17a9 4.5 0 1 0 18 0a9 4.5 0 1 0-18 0Zm4-1.5h10m-10 3h10M4 4q2-2 4 0t4 0t4 0t4 0M4 8.75q2-2 4 0t4 0t4 0t4 0");
}

</style>
