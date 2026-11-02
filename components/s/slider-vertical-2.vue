<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zymrr9x_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-2" /></template>
<style>
.zymrr9x_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 8a2 2 0 1 1 0 4a2 2 0 0 1 0-4m6 6a2 2 0 1 1 0 4a2 2 0 0 1 0-4m6-8a2 2 0 1 1 0 4a2 2 0 0 1 0-4M6 3v5m0 4v9m6-18v11m0 4v3m6-18v3m0 4v11");
}

</style>
