<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a10uvtbxk"/><path class="f5fedobno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-duotone-round" /></template>
<style>
.a10uvtbxk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V8c0-1.039.578-1.992 1.293-2.707l2-2C8.008 2.578 8.961 2 10 2h5a5 5 0 0 1 5 5Z");
}

.f5fedobno {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12v5a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V8c0-.64.36-1.36 1-2l2-2c.64-.64 1.36-1 2-1h5a4 4 0 0 1 4 4zm-9-5v3m3-3v3m3-3v3");
}

.ft5dv1b6b {
  fill: none;
}

</style>
