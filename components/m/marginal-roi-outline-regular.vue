<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfd41abkg"/><path class="y8ixl0bte"/><path class="hv2175vjd"/><path class="w0e70wbbt"/><path class="w08657bnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:marginal-roi-outline-regular" /></template>
<style>
.hv2175vjd {
  d: path("M17 16v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w08657bnd {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w0e70wbbt {
  d: path("M3 21.5h18");
}

.wfd41abkg {
  d: path("M5 10v9");
}

.y8ixl0bte {
  d: path("M11 13v6");
}

</style>
