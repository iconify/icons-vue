<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="etq4otbtt"/><rect class="d1hhgilos"/><circle class="fk37fwowk"/><path class="y2hi_gxpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myjio" /></template>
<style>
.d1hhgilos {
  width: 7.663px;
  height: 10.153px;
  x: 28.337px;
  y: 21.509px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.832px;
  ry: 3.832px;
}

.etq4otbtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.663 16.337v11.495a3.83 3.83 0 0 1-3.831 3.831h0A3.83 3.83 0 0 1 12 27.831V26.56");
}

.fk37fwowk {
  cx: 24.098px;
  cy: 18.071px;
  r: 0.75px;
  fill: currentColor;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.y2hi_gxpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.098 21.509v10.154");
}

</style>
