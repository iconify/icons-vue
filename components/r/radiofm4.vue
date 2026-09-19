<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="gmb06sbfn"/><rect class="j1rhcfbsq"/><path class="z_2gg2jzj"/><circle class="toebtob-k"/><path class="mitminbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:radiofm4" /></template>
<style>
.gmb06sbfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.28 38.417v-9.501l4.756 9.512l4.756-9.498v9.498m-16.694-9.512h4.756m-4.756 4.756h3.091m-3.091-4.756v9.512m24.206 0l-.001-9.512l-5.105 6.389H38.5");
}

.j1rhcfbsq {
  width: 4px;
  height: 5.3px;
  x: 30.205px;
  y: 21.456px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.mitminbxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.301 21.381v5.3m-7.802-1.925a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2m0 3.3v-5.3m5.805 2a2 2 0 0 0-2-2h0a2 2 0 0 0-2 2v1.3a2 2 0 0 0 2 2h0a2 2 0 0 0 2-2m0 2v-8");
}

.toebtob-k {
  cx: 28.301px;
  cy: 18.931px;
  r: 0.75px;
  fill: currentColor;
}

.z_2gg2jzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.098 23.456a2 2 0 0 1 2-2h0m-2 0v5.3");
}

</style>
