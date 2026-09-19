<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="e-uqlbb7e"/><circle class="ut1xs1bjo"/><path class="xkuen-bkc"/></g><g class="y9tr6bcfx"><circle class="hnl9ncatj"/><path class="s2joaaccx"/><circle class="bnfcmiboh"/><path class="qpdeej54g"/><circle class="unyea3xra"/><path class="t3uftrh9n"/><circle class="vrycm_1xn"/><path class="pym1nhb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playerpro" /></template>
<style>
.bnfcmiboh {
  cx: 7.635px;
  cy: 40.365px;
  r: 2.135px;
}

.e-uqlbb7e {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
}

.hnl9ncatj {
  cx: 7.635px;
  cy: 7.635px;
  r: 2.135px;
}

.pym1nhb9c {
  d: path("m38.826 38.887l3.018 3.017");
}

.qpdeej54g {
  d: path("m9.174 38.887l-3.018 3.017");
}

.s2joaaccx {
  d: path("M9.113 9.174L6.096 6.156");
}

.t3uftrh9n {
  d: path("m38.887 9.174l3.017-3.018");
}

.unyea3xra {
  cx: 40.365px;
  cy: 7.635px;
  r: 2.135px;
}

.ut1xs1bjo {
  cx: 24px;
  cy: 24px;
  r: 14.705px;
}

.vrycm_1xn {
  cx: 40.365px;
  cy: 40.365px;
  r: 2.135px;
}

.xkuen-bkc {
  d: path("M30.494 24L21.3 29.308V18.692z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
