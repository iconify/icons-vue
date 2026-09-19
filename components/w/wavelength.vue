<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="px3g7oqqi"/><path class="b6fx9mbgq"/><path class="r142512rp"/><path class="x-6sn_p-k"/><circle class="u79tmpbbn"/><circle class="djklj7q4v"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wavelength" /></template>
<style>
.b6fx9mbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.7 22.35l3.28 7.53h-3.7v5.96h-7.83v-7.52h-4.17l3.25-8.25");
}

.djklj7q4v {
  cx: 17.47px;
  cy: 18.27px;
  r: 0.75px;
  fill: currentColor;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.px3g7oqqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.04 16.25c2-4.65 4.65-8.14 9.87-8.14c5.63 0 10.11 4.48 10.11 10.05v24");
}

.r142512rp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.4 41.9V22.45c0-4.86 3.25-8.02 8.11-7.92c2.75.06 4.58.68 6.48 4.12m-4.02 10.28c0 1.88 2.95 3.17 5.18 3.17");
}

.u79tmpbbn {
  cx: 24.3px;
  cy: 20.81px;
  r: 0.75px;
  fill: currentColor;
}

.x-6sn_p-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.1 20.75l4.2-2.27l4.22 2.27l-4.23 2.4zm-6.84-2.55l4.2-2.26l4.22 2.27l-4.22 2.4zm8.81 17.64v6.64m6.07-6c1.42 0 2.63-2.44 2.63-3.9c0 1.49 1.25 3.9 2.62 3.9c-1.37 0-2.62 2.35-2.62 3.91c0-1.56-1.24-3.9-2.63-3.9M7.36 11.71c1.42 0 2.63-2.44 2.63-3.9c0 1.49 1.25 3.9 2.62 3.9c-1.37 0-2.62 2.35-2.62 3.91c0-1.56-1.24-3.9-2.63-3.9");
}

</style>
