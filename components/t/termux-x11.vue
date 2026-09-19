<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzq_7zbob"/><rect class="j3s9ivbxi"/><path class="zsruqhi1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:termux-x11" /></template>
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

.mzq_7zbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.5 25.327l10.127 5.853L10.5 37.032m22 0H21.673");
}

.zsruqhi1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.885 8.5h8.45c.643 0 1.165.686 1.165 1.533v7.715c0 .847-.522 1.533-1.165 1.533h-8.45c-.644 0-1.166-.686-1.166-1.533v-7.715c0-.847.522-1.533 1.166-1.533m-1.023 12.783h10.603M31.616 9.728l5.3 8m0-8l-5.3 8");
}

</style>
