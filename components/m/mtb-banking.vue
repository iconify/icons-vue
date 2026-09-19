<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rh1a4_ben"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mtb-banking" /></template>
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

.rh1a4_ben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.442L24 33.273l18.5-5.831m-14.425-6.169l-11.271-6.112l-8.916 5.44m11.874.981l5.789 2.439m-6.995.315l5.79 2.44m-6.995.315l5.789 2.439m1.752-12.007l5.678-2.796l9.61 6.077");
}

</style>
