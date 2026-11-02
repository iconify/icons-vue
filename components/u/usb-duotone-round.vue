<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wimns_bar"/><path class="pcnc85bai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pcnc85bai {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 6l3-3l3 3m-3-3v14m-4-5l4 4l4-4M4 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m12-1a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1Zm-6 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.wimns_bar {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.236 10.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 9h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2m-7.764 8.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
