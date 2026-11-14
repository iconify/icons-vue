<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhjb3lb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:star-burst" /></template>
<style>
.vhjb3lb2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.683 3.942za1.196 1.196 0 0 0 1.77.352a.787.787 0 0 1 1.261.523a1.196 1.196 0 0 0 1.501 1.002a.787.787 0 0 1 .966.966a1.196 1.196 0 0 0 1.002 1.501a.787.787 0 0 1 .523 1.261a1.196 1.196 0 0 0 .352 1.77a.787.787 0 0 1 0 1.366a1.196 1.196 0 0 0-.352 1.77a.787.787 0 0 1-.523 1.261a1.196 1.196 0 0 0-1.002 1.501a.787.787 0 0 1-.966.966a1.196 1.196 0 0 0-1.501 1.002a.787.787 0 0 1-1.261.523a1.196 1.196 0 0 0-1.77.352a.787.787 0 0 1-1.366 0a1.196 1.196 0 0 0-1.77-.352a.787.787 0 0 1-1.261-.523a1.196 1.196 0 0 0-1.501-1.002a.787.787 0 0 1-.966-.966a1.196 1.196 0 0 0-1.002-1.501a.787.787 0 0 1-.523-1.261a1.196 1.196 0 0 0-.352-1.77a.787.787 0 0 1 0-1.366a1.196 1.196 0 0 0 .352-1.77a.787.787 0 0 1 .523-1.261a1.196 1.196 0 0 0 1.002-1.501a.787.787 0 0 1 .966-.966a1.196 1.196 0 0 0 1.501-1.002a.787.787 0 0 1 1.261-.523a1.196 1.196 0 0 0 1.77-.352a.787.787 0 0 1 1.366 0");
}

</style>
