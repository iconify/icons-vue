<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crmcs2-ba"/><path class="mp34z4b_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallet-duocolor" /></template>
<style>
.crmcs2-ba {
  stroke-opacity: 0.4;
  d: path("M21 9h-4a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h4m-3-3h.01");
}

.mp34z4b_g {
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
