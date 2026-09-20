<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sy-b8bbxx"/><path class="ee7dg944u"/><path class="zugrvnb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ticket-scan-duotone-regular" /></template>
<style>
.ee7dg944u {
  d: path("M3 8h18v3l-2 2 2 2v3H3v-3l2 -2 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sy-b8bbxx {
  fill: currentColor;
  d: path("M3 8h18v3l-2 2 2 2v3H3v-3l2 -2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
