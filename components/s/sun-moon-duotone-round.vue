<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eresb-lku"/><path class="v7d_sgsms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-moon-duotone-round" /></template>
<style>
.eresb-lku {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9a4.268 4.268 0 0 0 6 6a6 6 0 1 1-6-6");
}

.ft5dv1b6b {
  fill: none;
}

.v7d_sgsms {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 15a6 6 0 1 1-6-6a4.269 4.269 0 0 0 6 6m-1.974-5.82a3 3 0 0 1 1.793 1.794M19 12h2m-9-7V3m4.95 4.05l1.414-1.414");
}

</style>
