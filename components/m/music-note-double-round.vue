<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzse_9bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-double-round" /></template>
<style>
.pzse_9bsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 0V8c0-1.838 2.162-2.919 4-2l2 1m-6 2l4 2");
}

</style>
