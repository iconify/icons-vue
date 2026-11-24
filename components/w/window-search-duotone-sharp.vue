<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vkjb21b8v"/><path class="hfk3qgb_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-search-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hfk3qgb_e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8V4h18v16H3zm0 0h18M9 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.vkjb21b8v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 4h18v4H3Z");
}

</style>
