<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zk3wb7b0x"/><rect class="kof-7sarc"/><path class="iz96dab5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paypay-stock" /></template>
<style>
.iz96dab5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 28v5m-8-5v5m-4-2.5V33m8-2.5V33m-8-7l4-3l4 3l4-3");
}

.kof-7sarc {
  width: 39px;
  height: 26px;
  x: 4.5px;
  y: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.zk3wb7b0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.5 37l4.886-20.369m-8.889-.686c9.187-.576 22.45 3.073 20.237 9.894C22.41 33.011 9.94 30.997 9.94 30.997");
}

</style>
