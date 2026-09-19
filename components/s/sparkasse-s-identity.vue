<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w15n67biq"/><g class="y9tr6bcfx"><path class="bglp60yyv"/><circle class="mxqmarbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sparkasse-s-identity" /></template>
<style>
.bglp60yyv {
  d: path("M9 26.4h12.4c1.7 0 3.1 1.4 3.1 3.1v9.9c0 1.7-1.4 3.1-3.1 3.1H9c-1.7 0-3.1-1.4-3.1-3.1v-9.9c0-1.7 1.4-3.1 3.1-3.1m1.3 5.4h14.3M5.9 37.1h14.3");
}

.mxqmarbxp {
  cx: 15.2px;
  cy: 23.3px;
  r: 3.1px;
}

.w15n67biq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.1 37.1h14.3m9-31.6v13.1m3.8 0V5.5h3c3.2 0 5.7 2.6 5.7 5.7v1.6c0 3.2-2.6 5.7-5.7 5.7h-3Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
