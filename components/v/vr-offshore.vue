<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jpqa3-brd"/><circle class="nx6yfrbvr"/><circle class="p-sedjbor"/><circle class="ugbdznmzn"/><circle class="ay1n0gbea"/><circle class="dcouawogc"/><circle class="le9n1k9nn"/><circle class="etmmosbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vr-offshore" /></template>
<style>
.ay1n0gbea {
  cx: 24.488px;
  cy: 33.59px;
  r: 0.75px;
  fill: currentColor;
}

.dcouawogc {
  cx: 27.459px;
  cy: 35.655px;
  r: 0.75px;
  fill: currentColor;
}

.etmmosbzc {
  cx: 29.625px;
  cy: 42.63px;
  r: 0.75px;
  fill: currentColor;
}

.jpqa3-brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.834 4.62c-2.569 1.209-8.487 7.101-10.325 10.652S17.16 21.92 17.16 21.92a9.5 9.5 0 0 0 2.795 2.493a13 13 0 0 0 3.4 1.133s4.004-5.44 4.532-7.026s3.098-8.536 2.947-13.9");
}

.le9n1k9nn {
  cx: 28.517px;
  cy: 39.142px;
  r: 0.75px;
  fill: currentColor;
}

.nx6yfrbvr {
  cx: 18.973px;
  cy: 25.903px;
  r: 0.75px;
  fill: currentColor;
}

.p-sedjbor {
  cx: 18.299px;
  cy: 29.479px;
  r: 0.75px;
  fill: currentColor;
}

.ugbdznmzn {
  cx: 21.416px;
  cy: 31.575px;
  r: 0.75px;
  fill: currentColor;
}

</style>
