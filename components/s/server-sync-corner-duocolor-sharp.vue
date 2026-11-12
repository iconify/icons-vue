<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bl-x8sbwt"/><path class="bxpv2lbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-sync-corner-duocolor-sharp" /></template>
<style>
.bl-x8sbwt {
  stroke-opacity: 0.4;
  d: path("M21 19a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-6a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

.bxpv2lbls {
  d: path("M3 4h18v6H3Zm0 10h6m0 6H3v-6m4-7h.01M7 17h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
