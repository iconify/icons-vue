<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="onxvj9b_v"/><path class="a0lh8-aox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-search-duotone-round" /></template>
<style>
.a0lh8-aox {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4zm0 0h18M9 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.onxvj9b_v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4Z");
}

</style>
