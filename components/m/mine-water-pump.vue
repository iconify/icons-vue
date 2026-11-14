<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_j76_bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-water-pump" /></template>
<style>
.s_j76_bjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5za4 4 0 0 1 4 4v4a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4m4 4.5H16a2.5 2.5 0 0 1 2.5 2.5m-16 11q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0m-2-8.25l2 3a2 2 0 0 1-4 0Z");
}

</style>
