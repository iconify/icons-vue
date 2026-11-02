<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu73ictjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-upload-corner-round" /></template>
<style>
.mu73ictjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v3m-3 11H7a4 4 0 0 1-4-4v-5m17 4l-3-3l-3 3m3-3v8");
}

</style>
