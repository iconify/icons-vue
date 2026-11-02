<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v3-1v9pyx"/><path class="iiby6ebor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iiby6ebor {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2zm7 9h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2z");
}

.v3-1v9pyx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 5a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Zm7 9a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2Z");
}

</style>
