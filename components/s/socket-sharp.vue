<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu5hfjtdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:socket-sharp" /></template>
<style>
.mu5hfjtdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v18H3Zm3 9a6 6 0 1 0 12 0a6 6 0 0 0-12 0m3 0a.5.5 0 1 0 1 0a.5.5 0 0 0-1 0m.5 0h.01M14 12a.5.5 0 1 0 1 0a.5.5 0 0 0-1 0m.5 0h.01");
}

</style>
