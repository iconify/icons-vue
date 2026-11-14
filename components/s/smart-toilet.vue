<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a00vh92dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-toilet" /></template>
<style>
.a00vh92dz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.688 3h1.125A2.19 2.19 0 0 1 9 5.188v3.625A2.19 2.19 0 0 1 6.813 11H5.688A2.19 2.19 0 0 1 3.5 8.813V5.188A2.19 2.19 0 0 1 5.688 3M3.5 11h17c0 3.5-2.5 6-6.25 6.25L15 21H8.5l.75-4.25C5.75 16 3.5 14 3.5 11m10.232-3.768a2.5 2.5 0 0 1 3.536 0M12.286 5.17a5 5 0 0 1 6.428 0");
}

</style>
