<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ktgbkob2k"/><path class="ticui_v2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-tracking-corner-duocolor-round" /></template>
<style>
.ktgbkob2k {
  stroke-opacity: 0.4;
  d: path("M17 21c-2-2-4-4-4-5a4 4 0 1 1 8 0c0 1-2 3-4 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ticui_v2g {
  d: path("M4 8v8a4 4 0 0 0 4 4M4 8l1-2c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2M4 8h16m-3 8h.01");
}

</style>
