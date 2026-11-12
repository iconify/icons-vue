<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkx22rbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-15" /></template>
<style>
.pkx22rbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8a8.944 8.944 0 0 1 16 0m-4 0h4V4M6 15l2-2v8m10-8h-6v4h2c2 0 4 0 4 2s-2 2-4 2h-2");
}

</style>
