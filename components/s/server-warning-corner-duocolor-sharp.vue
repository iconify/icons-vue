<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e906b4bdd"/><path class="bxpv2lbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-warning-corner-duocolor-sharp" /></template>
<style>
.bxpv2lbls {
  d: path("M3 4h18v6H3Zm0 10h6m0 6H3v-6m4-7h.01M7 17h.01");
}

.e906b4bdd {
  stroke-opacity: 0.4;
  d: path("M17 14v4m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
