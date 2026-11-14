<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1w0flbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scanner-3d" /></template>
<style>
.b1w0flbrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m9.25-8.067l2.397 1.384a1.5 1.5 0 0 1 .75 1.299v2.768a1.5 1.5 0 0 1-.75 1.299l-2.397 1.384a1.5 1.5 0 0 1-1.5 0l-2.397-1.384a1.5 1.5 0 0 1-.75-1.299v-2.768a1.5 1.5 0 0 1 .75-1.299l2.397-1.384a1.5 1.5 0 0 1 1.5 0M12 12v4.5m0-4.5L8.25 9.75M12 12l3.75-2.25");
}

</style>
