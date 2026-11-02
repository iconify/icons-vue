<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="us15sabgl"/><path class="jk12v_m5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trophy-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jk12v_m5i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9V3h10v6A5 5 0 0 1 7 9m3 5v2c0 2-3 2-3 5m7-7v2c0 2 3 2 3 5M6 21h12M7 5H5a2 2 0 1 0 0 4h2m10-4h2a2 2 0 1 1 0 4h-2");
}

.us15sabgl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v6a6 6 0 0 1-3 5.198V16c0 .18.069.349.178.491c.201.261.475.466.728.673c.228.186.455.374.669.576q.386.36.69.791c.503.726.735 1.591.735 2.469a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1c0-.878.232-1.743.735-2.469q.304-.431.69-.791c.214-.202.441-.39.669-.576c.253-.207.527-.412.728-.673A.8.8 0 0 0 9 16v-1.802A6 6 0 0 1 6 9Z");
}

</style>
