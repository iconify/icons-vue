<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nm5m83bee"/><path class="m1oqaxx_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-right-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m1oqaxx_v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4zm0 0h18m-6 0v12");
}

.nm5m83bee {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 9H3a1 1 0 0 1-1-1a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 7 3h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21h-2a1 1 0 0 1-1-1Z");
}

</style>
