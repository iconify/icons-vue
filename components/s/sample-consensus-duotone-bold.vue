<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gcm_1vbnz"/><path class="zleyw8bhf"/><path class="onu1akn2n"/><path class="reyu0nxyv"/><path class="evlitcc2y"/><path class="yrj3_cbwh"/><path class="vhfgw5-us"/><path class="gtg_qfbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sample-consensus-duotone-bold" /></template>
<style>
.evlitcc2y {
  d: path("M2 6h10");
}

.gcm_1vbnz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gtg_qfbzx {
  d: path("m15 12 2.5 2.5L22 10");
}

.onu1akn2n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.reyu0nxyv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 12 2.5 2.5L22 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vhfgw5-us {
  d: path("M2 16h10");
}

.yrj3_cbwh {
  d: path("M2 11h10");
}

.zleyw8bhf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
