<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="rcca7kb3x"/><path class="ooz7uo8fw"/><circle class="b58-lyb0b"/><circle class="ts9tz5b0x"/><circle class="xh264cb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wrong-pin-shutdown" /></template>
<style>
.b58-lyb0b {
  cx: 10.355px;
  cy: 34.687px;
  r: 1.682px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ooz7uo8fw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.407 38.05v-6.727M21.154 9.57a7.812 7.812 0 1 0 5.692 0M24 7.889v7.865");
}

.rcca7kb3x {
  width: 39px;
  height: 10.849px;
  x: 4.5px;
  y: 29.262px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.935px;
}

.ts9tz5b0x {
  cx: 24px;
  cy: 34.687px;
  r: 1.682px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xh264cb9k {
  cx: 17.177px;
  cy: 34.687px;
  r: 1.682px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
