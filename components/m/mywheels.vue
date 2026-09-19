<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dlnu___2h"/><circle class="h745n-s0q"/><circle class="hsjl02b8b"/><path class="xfvdbb15w"/><path class="g4vjnacmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mywheels" /></template>
<style>
.dlnu___2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.489 18.102c.82 0 1.62.252 2.292.722l1.455 1.016");
}

.g4vjnacmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.512 18.102c-.82 0-1.621.252-2.293.722l-1.455 1.016m0 0h-4.937c0-1.184-1.405-2.145-3.14-2.145s-3.14.96-3.14 2.145H9.236m3.366 13.033H9.023m26.375 0h3.579");
}

.h745n-s0q {
  cx: 13.985px;
  cy: 25.895px;
  r: 2.152px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hsjl02b8b {
  cx: 34.015px;
  cy: 25.895px;
  r: 2.152px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xfvdbb15w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.466 29.006H18.534m20.443 3.867v-11.06a9.3 9.3 0 0 0-.923-4.032l-2.228-4.607a3.56 3.56 0 0 0-3.203-2.009H15.377c-1.365 0-2.61.78-3.203 2.01L9.946 17.78a9.3 9.3 0 0 0-.923 4.032v13.64c0 .763.619 1.382 1.382 1.382h.814c.764 0 1.383-.62 1.383-1.383v-2.58h22.795v2.58c0 .764.62 1.383 1.383 1.383h.814c.764 0 1.383-.62 1.383-1.383z");
}

</style>
