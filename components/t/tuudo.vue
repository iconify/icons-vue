<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><rect class="fvfizpb2v"/><path class="egeijobri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tuudo" /></template>
<style>
.egeijobri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.852 21.521v3.754a2.275 2.275 0 0 0 4.55 0v-3.754m.001 3.754v2.275m2.139-6.029v3.754a2.275 2.275 0 0 0 4.55 0v-3.754m0 3.754v2.275m-14.398-7.906v7.906M9.5 21.521h2.389m19.857 2.275a2.275 2.275 0 0 0-4.55 0v1.48a2.275 2.275 0 0 0 4.55 0m0 2.274v-9.1");
}

.fvfizpb2v {
  width: 4.551px;
  height: 6.029px;
  x: 33.95px;
  y: 21.521px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.275px;
  ry: 2.275px;
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

</style>
