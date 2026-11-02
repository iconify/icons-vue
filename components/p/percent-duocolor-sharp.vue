<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ss58g-prf"/><path class="oqdxdpjwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:percent-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqdxdpjwb {
  d: path("M19 5L5 19");
}

.ss58g-prf {
  stroke-opacity: 0.4;
  d: path("M5 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
