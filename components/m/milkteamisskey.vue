<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3hf7vj2o"/><path class="az2j-nbey"/><circle class="kf77y5bfz"/><path class="ueyv1xs4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:milkteamisskey" /></template>
<style>
.az2j-nbey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.918 27.161V21.21l2.975 5.951l2.975-5.951v5.951m5.638-5.95v5.95m0-1.265l2.678-2.677m-1.86 1.86l2.158 2.082");
}

.i3hf7vj2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.22 8.083a1.72 1.72 0 0 0-1.72 1.72v28.395a1.72 1.72 0 0 0 1.72 1.72h28.395a1.73 1.73 0 0 0 1.72-1.72v-6.3c4.308 0 7.164-1.548 7.164-8.346c0-8.454-7.164-7.394-7.164-7.394V9.803a1.72 1.72 0 0 0-1.72-1.72Zm30.114 8.075v15.739");
}

.kf77y5bfz {
  cx: 14.754px;
  cy: 21.433px;
  r: 0.75px;
  fill: currentColor;
}

.ueyv1xs4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.754 23.219v3.942m1.883-5.95v5.95m12.169-.744a1.44 1.44 0 0 1-1.265.744a1.49 1.49 0 0 1-1.488-1.488v-.966a1.488 1.488 0 0 1 2.976 0v.52h-2.976m-2.375-3.273v4.463a.703.703 0 0 0 .744.744h.223m-1.71-3.942h1.562m9.421 2.455a1.488 1.488 0 1 1-2.976 0v-.967a1.488 1.488 0 1 1 2.976 0m.232 2.27v-3.942");
}

</style>
