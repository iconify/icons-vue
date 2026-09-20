<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="re1ycmbhy"/><rect class="b886s2wsk"/><path class="e5m7q-bdt"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onecard" /></template>
<style>
.b886s2wsk {
  width: 7.614px;
  height: 10.088px;
  x: 8.697px;
  y: 16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.807px;
  ry: 3.807px;
}

.e5m7q-bdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.783 26.088v-6.281a3.807 3.807 0 1 0-7.614 0m0 6.281V16m18.635 8.167a3.807 3.807 0 0 1-7.115-1.886v-2.474a3.807 3.807 0 1 1 7.614 0v1.237h-7.614M12.504 18.39v5.309m-1.12-4.586h.493a.627.627 0 0 0 .627-.627");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.re1ycmbhy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 32h39");
}

</style>
