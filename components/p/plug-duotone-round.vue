<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qb9bnmh0z"/><path class="kzlcwnntl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kzlcwnntl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Zm6 6v4M9 3v4m6-4v4");
}

.qb9bnmh0z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 11a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Z");
}

</style>
