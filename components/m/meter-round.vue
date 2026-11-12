<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny8d3bcmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-round" /></template>
<style>
.ny8d3bcmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v9a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm5-5v1m8-1v1M6 8a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Zm4-1v5m4-5v5m-6 5h8");
}

</style>
