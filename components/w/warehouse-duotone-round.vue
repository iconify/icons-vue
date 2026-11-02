<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hfhxlftau"/><path class="qvec0abqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hfhxlftau {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 12c0-1.693 1.069-3.152 2.553-3.894l4-2A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l4 2C18.931 8.848 20 10.307 20 12v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.qvec0abqb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M5 21v-9c0-1.226.774-2.387 2-3l4-2h2l4 2c1.226.613 2 1.774 2 3v9M9 21v-8h6v8m-6-4h6");
}

</style>
