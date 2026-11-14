<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvmdkibdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-gloves" /></template>
<style>
.uvmdkibdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15V7a3 3 0 0 1 6 0v2.5c1.25-.25 1.75.5 1.5 1.5L9 14v1m12 0V7a3 3 0 0 0-6 0v2.5c-1.25-.25-1.75.5-1.5 1.5l1.5 3v1M4 15h4a1.5 1.5 0 0 1 1.5 1.5V19A1.5 1.5 0 0 1 8 20.5H4A1.5 1.5 0 0 1 2.5 19v-2.5A1.5 1.5 0 0 1 4 15m12 0h4a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h-4a1.5 1.5 0 0 1-1.5-1.5v-2.5A1.5 1.5 0 0 1 16 15");
}

</style>
