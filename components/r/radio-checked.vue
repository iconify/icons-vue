<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_bmgbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-checked" /></template>
<style>
.s2_bmgbga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 0 0-16 0m5 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
