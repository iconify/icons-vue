<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(9.72 15.71 24)" class="q9pfaynbw"/><path class="xs09x9byd"/><circle class="kr-y_kbru"/><path class="n6r0n32cw"/><path class="p05w35iup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tcl-e-ticket" /></template>
<style>
.kr-y_kbru {
  cx: 15.709px;
  cy: 24px;
  r: 4.837px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n6r0n32cw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.141 24.012l1.391 1.965l3.874-2.741m3.35 13.125h18.513a2.23 2.23 0 0 0 2.23-2.23V17.018a2.23 2.23 0 0 0-2.23-2.23H25.451");
}

.p05w35iup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.424 22.842v5.668h2.834m-14.412-5.668h3.756m-1.878 5.668v-5.668m7.059 5.118a1.878 1.878 0 0 1-3.206-1.328V24.72a1.877 1.877 0 0 1 3.354-1.16");
}

.q9pfaynbw {
  width: 16.093px;
  height: 30.503px;
  x: 7.663px;
  y: 8.749px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.92px;
  ry: 1.92px;
}

.xs09x9byd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.809 36.101l5.494.941M13.36 8.124l.33 1.325a1.91 1.91 0 0 0 1.528 1.42l5.325.912a1.91 1.91 0 0 0 1.914-.83l.752-1.14");
}

</style>
