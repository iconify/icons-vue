<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oq65dqp9j"/><path class="aqh1fxw_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-duotone" /></template>
<style>
.aqh1fxw_d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.64.36-1.36 1-2l2-2c.64-.64 1.36-1 2-1h7a2 2 0 0 1 2 2zm-9-5v3m3-3v3m3-3v3");
}

.ft5dv1b6b {
  fill: none;
}

.oq65dqp9j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 19a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8c0-1.039.578-1.992 1.293-2.707l2-2C8.008 2.578 8.961 2 10 2h7a3 3 0 0 1 3 3Z");
}

</style>
