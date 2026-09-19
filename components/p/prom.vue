<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vb66ykb0b"/><path class="mr3_qc39r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prom" /></template>
<style>
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

.mr3_qc39r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.005 5.5v4.165h4.165v4.165h4.165v4.165H42.5m0 12.01h-4.165v4.165H34.17v4.165h-4.165V42.5m-12.01 0v-4.165H13.83V34.17H9.665v-4.165H5.5");
}

.vb66ykb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.83 13.83h20.34v20.34H13.83zM5.5 17.995h4.165V13.83h4.165V9.665h4.165V5.5");
}

</style>
