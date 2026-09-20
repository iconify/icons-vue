<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="awdfvlbgv"/><path class="bpf-4uzhw"/><path class="zfjwcz4-w"/><path class="npar3ybny"/><path class="evlitcc2y"/><path class="yrj3_cbwh"/><path class="vhfgw5-us"/><path class="gtg_qfbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sample-consensus-duotone-regular" /></template>
<style>
.awdfvlbgv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bpf-4uzhw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.evlitcc2y {
  d: path("M2 6h10");
}

.gtg_qfbzx {
  d: path("m15 12 2.5 2.5L22 10");
}

.npar3ybny {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 12 2.5 2.5L22 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vhfgw5-us {
  d: path("M2 16h10");
}

.yrj3_cbwh {
  d: path("M2 11h10");
}

.zfjwcz4-w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
