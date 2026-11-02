<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wckbc5bmz"/><path class="mndis4b8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-user-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mndis4b8g {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4a4 4 0 0 1 4 4v3c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V7a4 4 0 0 1 4-4zm-2 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-2 9a4.167 4.167 0 0 1 8 0");
}

.wckbc5bmz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 2a5 5 0 0 1 5 5v3c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V7a5 5 0 0 1 5-5Z");
}

</style>
