<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wx6_6sbdx"/><path class="s25jhik8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s25jhik8m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h1a2 2 0 0 1 2 2v1M3 18a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm18 0v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h2M6 16a4 4 0 0 1 4-4h4a4 4 0 0 1 1.176.176M5 2l17 17");
}

.wx6_6sbdx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3h1a2.003 2.003 0 0 1 2 2v1ZM9 6l2 2a2.003 2.003 0 0 1-2-2M5 16h2a2.003 2.003 0 0 1 2 2v1a2.003 2.003 0 0 1-2 2H5a2.003 2.003 0 0 1-2-2v-1a2.003 2.003 0 0 1 2-2m16 3a2.003 2.003 0 0 1-2 2h-2a2.003 2.003 0 0 1-2-2v-1a2.003 2.003 0 0 1 2-2h2l2 2Z");
}

</style>
