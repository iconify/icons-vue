<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mfoxnccay"/><path class="yvp_zcajf"/><circle class="jdisfxbxd"/><circle class="l1q1n3kez"/><circle class="gghkszigh"/><circle class="wuse59bng"/><circle class="lvpv7kboh"/><rect class="xham6sbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-keys-cafe" /></template>
<style>
.gghkszigh {
  cx: 14px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jdisfxbxd {
  cx: 24px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l1q1n3kez {
  cx: 24px;
  cy: 14px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lvpv7kboh {
  cx: 34px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mfoxnccay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 9.5v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4h29a4 4 0 0 1 4 4");
}

.wuse59bng {
  cx: 14px;
  cy: 14px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xham6sbcv {
  width: 27px;
  height: 7px;
  x: 10.5px;
  y: 30.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.5px;
  ry: 3.5px;
}

.yvp_zcajf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.875 12.588A2.088 2.088 0 0 0 34 11.512a2.088 2.088 0 0 0-3.735 1.822C30.955 15.322 34 17.5 34 17.5s3.045-2.18 3.735-4.165c.09-.232.14-.483.14-.747");
}

</style>
