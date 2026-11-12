<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pbjb7xbdp"/><path class="awo27eb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:page-margins-duotone-round" /></template>
<style>
.awo27eb6y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Zm4 2a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.pbjb7xbdp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 2h6a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5");
}

</style>
