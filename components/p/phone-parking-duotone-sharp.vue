<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m5pw_db0t"/><path class="g09fuuh-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-parking-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g09fuuh-n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5V3h6l2 5l-3 3l5 5l3-3l5 2v6h-2C10.163 21 3 13.837 3 5m13-2v6m0-6h2a2 2 0 1 1 0 4h-2");
}

.m5pw_db0t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h6l2 5l-3 3l5 5l3-3l5 2v6h-2C10.163 21 3 13.837 3 5Z");
}

</style>
