<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj9jv175p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-side" /></template>
<style>
.lj9jv175p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 4h3M5 18a2 2 0 0 1-2-2v-4l4-4c.64-.64 1.36-1 2-1h3c.64 0 1.36.36 2 1l4 4h1a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2M9 18h6M3 12h15m-8-5v5");
}

</style>
