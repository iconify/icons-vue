<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k630oypbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-warning-corner-round" /></template>
<style>
.k630oypbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4M8 20H7a4 4 0 0 1-4-4V8m0 0h18m-4 6v4m0 3h.01");
}

</style>
