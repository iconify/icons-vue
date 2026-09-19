<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gk72_2bys"/><path class="ae1y3nb8r"/><path class="xwu7d9bnn"/><path class="z1a41oxji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tabiwa-by-wester" /></template>
<style>
.ae1y3nb8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 19.984V35.5c0 2.216-1.783 4-4 4h-31c-2.215 0-4-1.784-4-4v-19c0-2.216 1.785-4 4-4h22.33");
}

.gk72_2bys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.784 39.5a21.46 21.46 0 0 1 0-27M18 12.5v-2c0-1.108.893-2 2-2h6c1.109 0 2 .892 2 2v2");
}

.xwu7d9bnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.56 12.5L35.944 26L11.56 39.5M40.21 9.324a6.13 6.13 0 0 0-5.71-.225c-2.085-.226-3.693.325-4.373 1.498c-1.234 2.141.906 5.693 4.779 7.933h0c3.873 2.24 8.012 2.321 9.246.18c.68-1.178.351-2.854-.89-4.553a6.15 6.15 0 0 0-3.051-4.833z");
}

.z1a41oxji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.459 17.731c-.617 1.07-3.499.56-6.437-1.139s-4.82-3.945-4.203-5.015");
}

</style>
