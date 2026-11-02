<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxp4o7b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-round" /></template>
<style>
.uxp4o7b8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3v9a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V3M3 3h18m-9 13l-5 5m5-5l5 5");
}

</style>
