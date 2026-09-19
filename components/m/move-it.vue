<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mpiypbe5t"/><rect class="dvoqn0yzh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:move-it" /></template>
<style>
.dvoqn0yzh {
  width: 3.916px;
  height: 5.911px;
  x: 17.048px;
  y: 21.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.958px;
  ry: 1.958px;
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

.mpiypbe5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.209 21.044v5.912M9.5 26.949v-5.905l2.956 5.912l2.955-5.903v5.903m19.173-5.912H38.5m-1.958 5.912v-5.912m-10.647 0l-1.958 5.912l-1.958-5.912M27.26 24h1.927m1.029 2.956H27.26v-5.912h2.956");
}

</style>
