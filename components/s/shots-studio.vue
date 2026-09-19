<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><rect class="qzafsbbdt"/><path class="h81a--b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shots-studio" /></template>
<style>
.h81a--b7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 34.278h4.111v4.111h-4.111zm-8.223 0h4.111v4.111h-4.111zm-8.222 0h4.111v4.111h-4.111zm-4.111-8.222v4.111h4.111V17.833h4.111v12.334h4.111V17.833h4.111v12.334h4.111l.001-12.334h4.111v12.334h4.111v-4.111z");
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

.qzafsbbdt {
  width: 28.778px;
  height: 12.333px;
  x: 9.611px;
  y: 9.611px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  ry: 0px;
}

</style>
