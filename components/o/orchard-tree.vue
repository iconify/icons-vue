<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ss2we_bgy"/><circle class="bndm1jvxx"/><path class="fvfnvuhbi"/><path class="q6nvdzbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orchard-tree" /></template>
<style>
.bndm1jvxx {
  cx: 18.25px;
  cy: 13.25px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fvfnvuhbi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 14v7.25m10-5.25v5.25m-15.5 0h18.5");
}

.q6nvdzbmm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 7.25h.01m3.99-.5h.01m-2.01 4h.01");
}

.ss2we_bgy {
  cx: 8.25px;
  cy: 8.5px;
  r: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
