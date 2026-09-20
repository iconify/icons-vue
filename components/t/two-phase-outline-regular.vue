<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h9i3bw3au"/><path class="n6_f133dv"/><path class="upuk2bbmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:two-phase-outline-regular" /></template>
<style>
.h9i3bw3au {
  d: path("m5 8 2 2 3.5 -3.5");
}

.n6_f133dv {
  d: path("m5 16 2 2 3.5 -3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.upuk2bbmi {
  d: path("M15.5 5H18v14h-2.5");
}

</style>
