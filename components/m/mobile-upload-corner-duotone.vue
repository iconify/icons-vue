<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r0y_vhbdg"/><path class="foupydbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-upload-corner-duotone" /></template>
<style>
.foupydbwb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v5m-3 11H5a2 2 0 0 1-2-2v-7m17 4l-3-3l-3 3m3-3v8");
}

.ft5dv1b6b {
  fill: none;
}

.r0y_vhbdg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 21a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v5a1 1 0 0 1-1 1h-1a.997.997 0 0 0-1 1Z");
}

</style>
