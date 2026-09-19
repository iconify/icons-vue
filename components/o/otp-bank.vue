<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dgke4cczh"/><circle class="gqr4mwb2o"/><path class="kgzkmerso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:otp-bank" /></template>
<style>
.dgke4cczh {
  cx: 24px;
  cy: 24px;
  r: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gqr4mwb2o {
  cx: 35.49px;
  cy: 12.51px;
  r: 5.273px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kgzkmerso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 24h10.5A21.499 21.499 0 0 1 8.798 39.202A21.5 21.5 0 0 1 24 2.5V13");
}

</style>
