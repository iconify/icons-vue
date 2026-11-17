<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cz0z_vbee"/><path class="n2c7r1c7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:water-heater-duotone" /></template>
<style>
.cz0z_vbee {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 6h8a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2");
}

.ft5dv1b6b {
  fill: none;
}

.n2c7r1c7n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 8a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2Zm3-5v3m6-3v3m-3 3c.25 1.25 1 2.25 2 3c.75.75 1 1.75 1 3a3 3 0 1 1-6 0c0-.75.25-1.25.5-1.5m0 0a1 1 0 1 0 2 0c0-.75-.25-1-.5-1.5c-.5-1-.25-2 1-3");
}

</style>
