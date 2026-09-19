<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akz56_b1q"/><circle class="tmj_teb7k"/><path class="etze-mboi"/><path class="vucfosbym"/><circle class="ff8rek74x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:usb-audio-player-pro" /></template>
<style>
.akz56_b1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.87 31.46v4.72c0 3.983 4.174 6.587 7.751 4.835l24.864-12.18c4.02-1.97 4.02-7.7 0-9.67L14.62 6.985c-3.576-1.752-7.752.852-7.752 4.835v4.72");
}

.etze-mboi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.442 23.627h10.3m-5.054-3.895H12.51l-1.463 3.895l2.496 4.641h2.162m7.951-4.641l-3.914-2.26v4.519z");
}

.ff8rek74x {
  cx: 16.102px;
  cy: 19.732px;
  r: 1.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tmj_teb7k {
  cx: 7.471px;
  cy: 23.627px;
  r: 1.971px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vucfosbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.705 27.012h2.511v2.511h-2.511z");
}

</style>
