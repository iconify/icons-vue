<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m_8w5-bkq"/><path class="f79py29fw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-duotone-round" /></template>
<style>
.f79py29fw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12V7a4 4 0 0 1 4-4h4c1.28 0 2.36.36 3 1l2 2c.64.64 1 1.72 1 3v8a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4zm4-1a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Zm0 2h6");
}

.ft5dv1b6b {
  fill: none;
}

.m_8w5-bkq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 7a5 5 0 0 1 5-5h4c1.317 0 2.748.335 3.707 1.293l2 2C19.665 6.252 20 7.683 20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5Z");
}

</style>
