<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gfpi4zbgi"/><path class="qgyow-_uj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:voicemail-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gfpi4zbgi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 15a3 3 0 1 1 0-6a3 3 0 0 1 0 6m12 0a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

.qgyow-_uj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-9 3h12");
}

</style>
