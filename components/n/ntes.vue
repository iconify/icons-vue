<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mxajs-uri"/><path class="zix8gp11o"/><rect class="stjgbvj-x"/><circle class="yo5a92sqr"/><path class="guq42acaa"/><circle class="r3lqqb5py"/><path class="wcm1lfbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ntes" /></template>
<style>
.guq42acaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.132 10.093l3.49 2.412m-14.923-2.412l3.49 2.412M19.76 4.5h8.525m8.467 39l-4.208-7.8");
}

.mxajs-uri {
  width: 26.222px;
  height: 28.583px;
  x: 10.889px;
  y: 7.117px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.72px;
}

.r3lqqb5py {
  cx: 33.416px;
  cy: 31.851px;
  r: 2.001px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.stjgbvj-x {
  width: 21.809px;
  height: 10.263px;
  x: 13.095px;
  y: 10.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.642px;
}

.wcm1lfbqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.085 38.368H33.96m-21.75 3.387h23.624");
}

.yo5a92sqr {
  cx: 14.584px;
  cy: 31.851px;
  r: 2.001px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zix8gp11o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.022 7.117V4.5m-12.774 39l4.208-7.8m4.304-8.108h8.525m-8.525-2.206h8.525");
}

</style>
