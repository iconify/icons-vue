<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="beqsa12ge"/><circle class="oynlhd-_h"/><path class="rdqtudw5i"/><circle class="v-yjnlqgj"/><circle class="jd3d8qyyo"/><path class="rbbw06b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tohobank" /></template>
<style>
.beqsa12ge {
  cx: 33.25px;
  cy: 14.75px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jd3d8qyyo {
  cx: 33.25px;
  cy: 33.25px;
  r: 3.083px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oynlhd-_h {
  cx: 33.25px;
  cy: 33.25px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rbbw06b5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 13.429H24m-18.5 0h6.167m29.274 24.96H42.5m-18.5 0h1.559m13.505 2.055H42.5m-18.5 0h3.436M24 42.5h18.5M24 24h18.5m-3.436 2.056H42.5m-18.5 0h3.436m13.505 2.055H42.5m-18.5 0h1.559M17.833 15.19H24m-18.5 0h6.167m6.166 1.762H24m-18.5 0h6.167m6.166 1.762H24m-18.5 0h6.167m6.166 1.762H24m-18.5 0h6.167m6.166 1.762H24m-18.5 0h6.167m6.166-10.571H24V5.5H5.5v6.167h6.167V24h6.166zM11.667 42.5h6.167M24 5.5h18.5V24H24z");
}

.rdqtudw5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 36.333V42.5H5.5V24h6.167v6.166h6.167V24H24v18.5h-6.167v-6.167z");
}

.v-yjnlqgj {
  cx: 33.25px;
  cy: 14.75px;
  r: 3.083px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
