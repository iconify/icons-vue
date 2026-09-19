<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3bc2bckk"/><circle class="uzlz1ur-r"/><circle class="k22un58bz"/><circle class="fwt3yubnb"/><path class="gwdk1jbbk"/><path class="gsfqxgpzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:osmonitor" /></template>
<style>
.fwt3yubnb {
  cx: 31.31px;
  cy: 37.16px;
  r: 0.75px;
  fill: currentColor;
}

.gsfqxgpzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.32 22.6h6.49l2.53-8.61l4.29 15.79L24 17.97l2.18 7.68L28 22.6h12.68");
}

.gwdk1jbbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.32 8.17h33.36v26.06H7.32z");
}

.j3bc2bckk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.74h37a1 1 0 0 1 1 1v31.72a1 1 0 0 1-1 1h-37a1 1 0 0 1-1-1V6.74a1 1 0 0 1 1-1");
}

.k22un58bz {
  cx: 35.79px;
  cy: 37.16px;
  r: 0.75px;
  fill: currentColor;
}

.uzlz1ur-r {
  cx: 40.27px;
  cy: 37.16px;
  r: 0.75px;
  fill: currentColor;
}

</style>
