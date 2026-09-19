<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lzzdeqbvv"/><circle class="hnlvnbcvz"/><circle class="wy67n1b0n"/><path class="w3uyjkmqj"/><circle class="d17jxvxpp"/><circle class="zny0fxgeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-camera-assistant" /></template>
<style>
.d17jxvxpp {
  cx: 31px;
  cy: 17px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hnlvnbcvz {
  cx: 11px;
  cy: 21px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lzzdeqbvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.5 28.5h15a4 4 0 0 0 4-4v-15a4 4 0 0 0-4-4h-15a4 4 0 0 0-4 4v15a4 4 0 0 0 4 4m-12.5-2V37m0-31.5v10");
}

.w3uyjkmqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37h-7.5m26 0H35");
}

.wy67n1b0n {
  cx: 29.5px;
  cy: 37px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zny0fxgeu {
  cx: 37px;
  cy: 11px;
  r: 0.75px;
  fill: currentColor;
}

</style>
