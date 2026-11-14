<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgia2gayz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pedestrian-crossing" /></template>
<style>
.tgia2gayz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 9l-1 4.5L8 18m3-4.5l3 1.5l.5 3.5m-6-6.5L10 9.5l2-.5l2.5 1.5l2 2M3 21.5h4m3 0h4m3 0h4");
}

</style>
