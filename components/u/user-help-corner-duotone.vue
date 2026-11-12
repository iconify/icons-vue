<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mqzlugbkx"/><path class="o2u0mcbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-help-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mqzlugbkx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.393 5.053a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M10 15v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

.o2u0mcbnq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 0 1 6-6m6 1a2 2 0 1 1 2 2m0 3h.01");
}

</style>
