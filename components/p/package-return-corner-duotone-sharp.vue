<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pe-0h2bzk"/><path class="ohe9ahbhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-return-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ohe9ahbhd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v12h4M4 8l2-4h12l2 4M4 8h16m1 5v4h-8m3-3l-3 3l3 3");
}

.pe-0h2bzk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.106 3.553A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4A1 1 0 0 1 20 9H4a1 1 0 0 1-.894-1.447Z");
}

</style>
