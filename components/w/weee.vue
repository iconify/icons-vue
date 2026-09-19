<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lbc69sb7k"/><path class="aoqeupb1e"/><path class="fw412lhhl"/><circle class="u25v0xmch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weee" /></template>
<style>
.aoqeupb1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.84 27.133c1.949-.143 4.203-.716 4.203-2.528c0-1.766-4.26-1.974-4.26 1.728c0 3.884 3.61 3.858 6.481 1.806");
}

.fw412lhhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.073 27.128c1.948-.143 4.142-.711 4.142-2.523c0-1.766-4.26-1.974-4.26 1.728c0 3.884 4.595 4.469 7.206.24M19.68 18.857c-.663 2.962-4.58 10.133-6.782 10.133c-1.442 0 .78-5.554-.448-10.133c.297 3.16-4.287 10.133-5.943 10.133s.565-9.665-.643-9.665s-1.364.331-1.364.331m39-1.169c-1.5 1.812-2.475 4.403-2.864 7.19");
}

.lbc69sb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.668 27.133c1.948-.143 4.203-.716 4.203-2.528c0-1.766-4.26-1.974-4.26 1.728c0 3.884 3.61 3.858 6.481 1.806");
}

.u25v0xmch {
  cx: 40.168px;
  cy: 28.451px;
  r: 1.052px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
