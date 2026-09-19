<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="frqu5jjdb"/><circle class="d1pegib1f"/><path class="mtmujgblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-afip" /></template>
<style>
.d1pegib1f {
  cx: 35.212px;
  cy: 11.777px;
  r: 0.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.frqu5jjdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.398 27.532V11.269l8.069 16.281l8.068-16.256V27.55");
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

.mtmujgblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.212 16.763V27.55m-8.315 4.219v4.962m3.19 0v-4.962h1.705c.964 0 1.745.746 1.745 1.666s-.781 1.667-1.745 1.667h-1.705m-8.984-.852h1.693m-1.693 2.481v-4.962h2.604m-6.365 3.318h-2.308m-.571 1.644l1.725-4.962l1.725 4.962");
}

</style>
