<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2cw-qbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-off-duotone-round" /></template>
<style>
.x2cw-qbsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 16a3.606 3.606 0 0 1 5-1m-8-2a7.8 7.8 0 0 1 4-2m-7-1a12 12 0 0 1 3-3m9 4a7.8 7.8 0 0 1 4 3m-9-8a12.04 12.04 0 0 1 11 4m-9 9h.01M2 3l19 19");
}

</style>
