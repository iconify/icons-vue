<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o6pe93y9q"/><path class="ik50jbv6y"/><path class="rq458iy4q"/><path class="bbi0or-0w"/><path class="v_5ltlgqc"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pts-ptm" /></template>
<style>
.bbi0or-0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 26.909c10.792-13.105 26.208-13.105 37 0");
}

.ik50jbv6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.125 42.5c0-21.045 27.75-21.045 27.75 0");
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

.o6pe93y9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 42.5c0-13.337 18.5-13.337 18.5 0");
}

.rq458iy4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.61 39.41c4.11-22.31 32.67-22.31 36.78 0");
}

.v_5ltlgqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.971q18.5-15.03 37 0");
}

</style>
