<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="mnco2zcal"/><path class="mizic_bbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:notebook-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mizic_bbc {
  d: path("M2 7L8 7M2 12L8 12M2 17L8 17");
}

.mnco2zcal {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1L21 1C21.5523 1 22 1.4477 22 2L22 22C22 22.5523 21.5523 23 21 23L5 23C4.4477 23 4 22.5523 4 22L4 2C4 1.4477 4.4477 1 5 1ZM18 5L16 5L16 19L18 19L18 5Z");
  stroke: none;
}

</style>
