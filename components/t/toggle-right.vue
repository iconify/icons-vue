<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p179t_bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-right" /></template>
<style>
.p179t_bns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a6 6 0 0 1 6-6h6a6 6 0 1 1 0 12H9a6 6 0 0 1-6-6m9 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
