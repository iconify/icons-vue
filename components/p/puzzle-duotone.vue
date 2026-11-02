<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j1qzc6cwh"/><path class="ttkw2ackr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j1qzc6cwh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 7a2 2 0 0 1 2 2v3a2.235 2.235 0 1 0 0 4v3a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-3a2.235 2.235 0 1 1 0-4V9a2 2 0 0 1 2-2h3a2.235 2.235 0 1 1 4 0Z");
}

.ttkw2ackr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 7h3a2 2 0 0 1 2 2v3a2.236 2.236 0 1 0 0 4v3a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-3a2.236 2.236 0 1 1 0-4V9a2 2 0 0 1 2-2h3a2.236 2.236 0 1 1 4 0");
}

</style>
