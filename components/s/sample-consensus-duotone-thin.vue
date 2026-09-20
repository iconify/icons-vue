<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qufsitwim"/><path class="qrmlt6bts"/><path class="cia0y5byl"/><path class="dmzu2f0ee"/><path class="evlitcc2y"/><path class="yrj3_cbwh"/><path class="vhfgw5-us"/><path class="gtg_qfbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sample-consensus-duotone-thin" /></template>
<style>
.cia0y5byl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dmzu2f0ee {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 12 2.5 2.5L22 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.evlitcc2y {
  d: path("M2 6h10");
}

.gtg_qfbzx {
  d: path("m15 12 2.5 2.5L22 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrmlt6bts {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qufsitwim {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhfgw5-us {
  d: path("M2 16h10");
}

.yrj3_cbwh {
  d: path("M2 11h10");
}

</style>
