<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o8te6lb4v"/><path class="xtv8je8bw"/><path class="nq1z19bud"/><path class="amdyfrbnw"/><path class="djifetbcn"/><path class="x2rmxpb0x"/><path class="bv72su-ri"/><path class="autc-bc3p"/><path class="bvirm9d4j"/><path class="a2pxmcc-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reranker-duotone-regular" /></template>
<style>
.a2pxmcc-f {
  d: path("m18 16 2 2 2 -2");
}

.amdyfrbnw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.autc-bc3p {
  d: path("M3 18h13");
}

.bv72su-ri {
  d: path("M3 12h13");
}

.bvirm9d4j {
  d: path("M20 6v12");
}

.djifetbcn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 16 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nq1z19bud {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8te6lb4v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x2rmxpb0x {
  d: path("M3 6h13");
}

.xtv8je8bw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
