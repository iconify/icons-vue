<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eu5ifdchi"/><path class="hpwyywbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sensor-duocolor-sharp" /></template>
<style>
.eu5ifdchi {
  stroke-opacity: 0.4;
  d: path("M17 11a4 4 0 0 0-4-4m8 4a8 8 0 0 0-8-8");
}

.hpwyywbvz {
  d: path("M3 11h10v10H3Zm5 0v10m-5-5h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
