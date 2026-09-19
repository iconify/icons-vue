<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="k7--nbc3n"/><circle class="j4wgh7jgi"/><path class="v4axtobty"/><circle class="pgp1_4tpn"/><circle class="sgz5n_ozp"/><path class="dq-4__bbc"/><circle class="xwh4lcb6r"/><path class="tfpse3nhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:royalsortballpuzzle" /></template>
<style>
.dq-4__bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.138 16.648v19.305a5.18 5.18 0 1 0 10.362 0V16.648Z");
}

.j4wgh7jgi {
  cx: 10.681px;
  cy: 35.614px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k7--nbc3n {
  cx: 24px;
  cy: 9.867px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pgp1_4tpn {
  cx: 37.319px;
  cy: 35.614px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sgz5n_ozp {
  cx: 37.319px;
  cy: 26.988px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tfpse3nhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.82 16.648v19.305a5.18 5.18 0 1 0 10.36 0V16.648Z");
}

.v4axtobty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.648v19.305a5.18 5.18 0 1 0 10.362 0V16.648Z");
}

.xwh4lcb6r {
  cx: 24px;
  cy: 35.614px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
