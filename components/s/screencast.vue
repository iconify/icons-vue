<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="uhx3m_1tm"/><rect class="fdicn9bbo"/><rect class="xjcygexuf"/><rect class="mx47gch7i"/><path class="a153q-ccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screencast" /></template>
<style>
.a153q-ccr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.71 12.6h14.62a1.61 1.61 0 0 1 1.61 1.61V16l4-2.29v9.16l-4-2.29v1.79A1.61 1.61 0 0 1 29.33 24H14.71a1.61 1.61 0 0 1-1.62-1.62v-8.17a1.61 1.61 0 0 1 1.62-1.61");
}

.fdicn9bbo {
  width: 4.74px;
  height: 4.74px;
  x: 21.63px;
  y: 32.22px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.mx47gch7i {
  width: 4.74px;
  height: 4.74px;
  x: 29.86px;
  y: 32.22px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.xjcygexuf {
  width: 4.74px;
  height: 4.74px;
  x: 13.4px;
  y: 32.22px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
