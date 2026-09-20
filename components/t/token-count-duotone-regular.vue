<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hayeafbtu"/><path class="ut3obm4bb"/><path class="q1of63b1x"/><path class="ctt_dn_1e"/><path class="wae8aklke"/><path class="oib43sizw"/><path class="fezibpbwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-count-duotone-regular" /></template>
<style>
.ctt_dn_1e {
  d: path("M2 11a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
}

.fezibpbwf {
  d: path("M3 18h10");
}

.hayeafbtu {
  fill: currentColor;
  d: path("M2 11a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oib43sizw {
  d: path("M18 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.q1of63b1x {
  fill: currentColor;
  d: path("M18 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ut3obm4bb {
  fill: currentColor;
  d: path("M10 11a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wae8aklke {
  d: path("M10 11a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
}

</style>
