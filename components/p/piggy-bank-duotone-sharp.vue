<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k2lvhdceu"/><path class="tu5_sx12l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:piggy-bank-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k2lvhdceu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 5a2 2 0 1 1 3.999-.001A2 2 0 0 1 7 5m6 6l3-3v3h-1a3 3 0 0 1 3 3v-1h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1v-1a3 3 0 0 1-3 3H8a4 4 0 0 1 0-8Z");
}

.tu5_sx12l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 11h4a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8a4 4 0 1 1 0-8zm2 0l3-3v3Zm5 2h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1zm-3 1h.01M7 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m1 14v2m6-2v2");
}

</style>
