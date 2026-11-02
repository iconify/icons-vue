<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xaw3pz4jn"/><path class="ui6j-ib1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ui6j-ib1k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3v11a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3M3 3h18m-9 13l-5 5m5-5l5 5");
}

.xaw3pz4jn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 2a1 1 0 0 1 1 1v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V3a1 1 0 0 1 1-1Z");
}

</style>
