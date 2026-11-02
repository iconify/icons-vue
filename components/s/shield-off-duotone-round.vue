<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wckbc5bmz"/><path class="c0f-csq0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-duotone-round" /></template>
<style>
.c0f-csq0v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h6a4 4 0 0 1 4 4v3c0 .958.2 1.16 0 2m-2 5c-1.441 1.847-3.721 2.987-6 4c-4.5-2-8-5.5-8-11V7c0-1.105.276-2.276 1-3M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.wckbc5bmz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 2a5 5 0 0 1 5 5v3c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V7a5 5 0 0 1 5-5Z");
}

</style>
