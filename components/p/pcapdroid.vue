<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_q-npdys"/><circle class="bk1pcxdtn"/><path class="reiuehbjd"/><circle class="iqnbw93xs"/><path class="v2k_1bdtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pcapdroid" /></template>
<style>
.bk1pcxdtn {
  cx: 19.191px;
  cy: 19.19px;
  r: 13.691px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e_q-npdys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.911 32.208l3.296-3.296L42.5 39.205L39.204 42.5z");
}

.iqnbw93xs {
  cx: 19.191px;
  cy: 19.19px;
  r: 9.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.reiuehbjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.559 30.56l-1.691-1.691");
}

.v2k_1bdtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.408 22.277h3.087m-3.087-5.333l1.544-.84m0 0v6.173m-11.747 0h1.85m-1.917-5.97l.374-.203m0 0v6.173m3.222-2.045a2.045 2.045 0 0 0 4.09 0v-2.083a2.045 2.045 0 0 0-4.09 0zm14.47-4.058a2.047 2.047 0 0 0-2.58 1.974v2.084a2.047 2.047 0 0 0 2.579 1.974");
}

</style>
