<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twnlmab2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword" /></template>
<style>
.twnlmab2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L17 4c.64-.64 1.36-1 2-1h2v2c0 .64-.36 1.36-1 2L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

</style>
