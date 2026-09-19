<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3gi1-bvq"/><rect class="trekdzbdm"/><path class="n-06-2bpf"/><path class="i_2t-k_fo"/><path class="w0o236b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:translate-you" /></template>
<style>
.i_2t-k_fo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.005 25.352h5.474m-3.703.026c-.868 7.993-4.674 10.7-11.52 12.743");
}

.n-06-2bpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.835 30.17v8.69c0 2 1.64 3.64 3.64 3.64h17.38c2 0 3.64-1.64 3.64-3.64V21.47c0-2-1.64-3.64-3.64-3.64h-8.69");
}

.trekdzbdm {
  width: 24.67px;
  height: 24.67px;
  x: 5.505px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 3.64px;
  ry: 3.64px;
}

.u3gi1-bvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.625 24.31l5.32-12.89m5.1 12.93l-5.1-12.93m3.4 8.6h-6.95");
}

.w0o236b6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.124 32.449c1.932 2.881 5.008 4.405 9.254 5.672");
}

</style>
