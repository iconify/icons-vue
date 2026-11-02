<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="isvey_b9m"/><path class="u9ghn-evg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suv-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.isvey_b9m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.829 19a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16v-6a5 5 0 0 1 5-5h6c.265 0 .52.105.707.293L17.414 9H19a3 3 0 0 1 3 3v4c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128Zm-3.538-.295l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

.u9ghn-evg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4h6l4 4h2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2M9 18h6M3 10h14m-7-4v4m-5 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
