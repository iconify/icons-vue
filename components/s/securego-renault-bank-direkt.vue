<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ptj6fcb1y"/><path class="fr3ru-g2o"/><g class="y9tr6bcfx"><circle class="pagdhwbzp"/><path class="kl841tnok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:securego-renault-bank-direkt" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fr3ru-g2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.791 20.532h12.53v9.403c-.014.506-.354.843-.842.843H18.707c-.572 0-1.045-.544-1.045-1.045zm2.309 0v-1.883a3.85 3.85 0 1 1 7.7 0v1.883");
}

.kl841tnok {
  d: path("M24 26.373v1.848");
}

.pagdhwbzp {
  cx: 24px;
  cy: 24.731px;
  r: 1.642px;
}

.ptj6fcb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 38.756c1.485 0 13.402-4.995 13.402-11.938V12.865L24 9.275l-13.402 3.59v13.953c0 6.943 11.917 11.938 13.402 11.938M12.388 5.915v6.474m0 19.12v10.595");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
