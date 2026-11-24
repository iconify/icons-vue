<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="plo_2nb-c"/><path class="mn2r8pb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-edit-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mn2r8pb2w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm6 14H5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h4M7 7h.01M7 17h.01M13 21v-3l5-5l3 3l-5 5Z");
}

.plo_2nb-c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 4h14a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m8 17v-3l5-5l3 3l-5 5Zm-4-1H5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h4Z");
}

</style>
