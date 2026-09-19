<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w3au52mgg"/><rect class="hm0w1jymd"/><rect class="t0adub2vj"/><circle class="za-1u13wn"/><path class="o2xjhrw1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rhythm" /></template>
<style>
.hm0w1jymd {
  width: 8.054px;
  height: 15.553px;
  x: 5.5px;
  y: 23.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.209px;
  ry: 3.209px;
}

.o2xjhrw1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.45 28.372l-9.884-5.706a1.2 1.2 0 0 0-1.8 1.039v11.413a1.2 1.2 0 0 0 1.8 1.04l9.885-5.708a1.2 1.2 0 0 0 0-2.078");
}

.t0adub2vj {
  width: 8.054px;
  height: 15.553px;
  x: 34.446px;
  y: 23.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.209px;
  ry: 3.209px;
}

.w3au52mgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.955 23.535v-1.478c0-7.685 5.393-13.914 12.045-13.914s12.045 6.23 12.045 13.914v1.347");
}

.za-1u13wn {
  cx: 24px;
  cy: 29.411px;
  r: 10.446px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
