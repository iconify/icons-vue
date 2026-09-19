<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yd9t56zub"/><path class="n2dipstds"/><path class="o_27mybvt"/><path class="gvk31vbue"/><path class="guytj_wyl"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uniqlo" /></template>
<style>
.guytj_wyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.223 33.555l-2.73-2.835");
}

.gvk31vbue {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M16.493 33.555a2.71 2.71 0 0 1-2.73-2.69V27.99c0-1.575 1.26-2.835 2.73-2.835c1.575 0 2.73 1.26 2.73 2.835v2.73c0 1.575-1.155 2.835-2.73 2.835Z");
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

.n2dipstds {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M31.402 33.555a2.71 2.71 0 0 1-2.73-2.69V27.99c0-1.575 1.26-2.835 2.73-2.835a2.823 2.823 0 0 1 2.835 2.835v2.73a2.823 2.823 0 0 1-2.835 2.835Z");
}

.o_27mybvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.763 14.445v5.565c0 1.575 1.26 2.835 2.73 2.835s2.835-1.26 2.835-2.835v-5.565");
}

.yd9t56zub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.346 25.155v8.4h4.2m4.909-19.11v8.4m-9.109 0v-8.4l5.565 8.4v-8.4");
}

</style>
