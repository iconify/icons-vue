<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="hc-xipzmx"/><circle class="hc-xipzmx"/><circle class="erk6zgbhe"/><circle class="erk6zgbhe"/><circle class="fico5f1ll"/><circle class="fico5f1ll"/><circle class="t94-x1bff"/><circle class="t94-x1bff"/><circle class="uejpsfx1m"/><circle class="uejpsfx1m"/><circle class="ju_h5ebbs"/><circle class="ju_h5ebbs"/><circle class="q8zfdybii"/><circle class="q8zfdybii"/><circle class="tlkhku-6p"/><circle class="tlkhku-6p"/><circle class="l-3g5-bns"/><path class="wc7sepepq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yubico-authenticator" /></template>
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

.erk6zgbhe {
  cx: 42px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.fico5f1ll {
  cx: 36.728px;
  cy: 36.728px;
  r: 0.75px;
  fill: currentColor;
}

.hc-xipzmx {
  cx: 36.728px;
  cy: 11.272px;
  r: 0.75px;
  fill: currentColor;
}

.ju_h5ebbs {
  cx: 6px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.l-3g5-bns {
  cx: 24px;
  cy: 24px;
  r: 15.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q8zfdybii {
  cx: 11.272px;
  cy: 11.272px;
  r: 0.75px;
  fill: currentColor;
}

.t94-x1bff {
  cx: 24px;
  cy: 42px;
  r: 0.75px;
  fill: currentColor;
}

.tlkhku-6p {
  cx: 24px;
  cy: 6px;
  r: 0.75px;
  fill: currentColor;
}

.uejpsfx1m {
  cx: 11.272px;
  cy: 36.728px;
  r: 0.75px;
  fill: currentColor;
}

.wc7sepepq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.29 32.5l8.943-17M24 27.349L17.767 15.5");
}

</style>
