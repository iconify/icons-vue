<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="fto5-kbbb"/><circle class="z64qlpb3o"/><path class="nzy50gn2o"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokegenie" /></template>
<style>
.fto5-kbbb {
  cx: 14.484px;
  cy: 19.372px;
  r: 7.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.nzy50gn2o {
  fill: none;
  stroke: currentColor;
  d: path("M42.5 22.64H29.794s-2.605-.428-5.599 3.383l-2.024 2.642c-2.993 3.81-5.598 3.382-5.598 3.382H5.5");
}

.z64qlpb3o {
  cx: 14.484px;
  cy: 19.372px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
