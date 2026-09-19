<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="o99npcbso"/><rect class="byk-ihmmr"/><rect class="ffxesnbri"/><path class="lkhq_8blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zozotown" /></template>
<style>
.byk-ihmmr {
  width: 5.3px;
  height: 8px;
  x: 16.067px;
  y: 25.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.ffxesnbri {
  width: 5.3px;
  height: 8px;
  x: 18.018px;
  y: 14.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
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

.lkhq_8blk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 33.5v-8l5.3 8v-8m-7.87 0l-2 8l-2-8l-2 8l-2-8m-13.23-11H16l-5.3 8H16m9.33-8h5.3l-5.3 8h5.3m4.674-8a2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 0 1-2.65 2.65h0a2.65 2.65 0 0 1-2.65-2.65v-2.7a2.65 2.65 0 0 1 2.65-2.65");
}

.o99npcbso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.2 25.5h5.3m-2.65 8v-8");
}

</style>
