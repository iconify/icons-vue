<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-_31z2eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-ping" /></template>
<style>
.k-_31z2eo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0M17 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 11c4 0 7 3 7 7M5 5c7 0 13 6 13 13");
}

</style>
