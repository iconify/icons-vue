<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="so18xfj7v"/><path class="xaoz6ui_x"/><path class="hwkycubpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oneui-dark" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hwkycubpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.75 13.166c-.372.94-.745 1.879-1.409 2.409c-.663.53-1.616.65-2.57.772m7.687 3.887h8.705m-8.747 4.85h8.85m-8.767 4.456h8.684");
}

.so18xfj7v {
  cx: 11.734px;
  cy: 24.54px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xaoz6ui_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.4 29.54V18.959l8.352 10.083V13.164");
}

</style>
