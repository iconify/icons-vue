<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kirvrcbjb"/><path class="shqfdzbah"/><path class="a70_cibzt"/><path class="a83b_cc0a"/><circle class="z_o1-ebmc"/><path class="q1a9arbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:towerjumper" /></template>
<style>
.a70_cibzt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.81 24.82l-17.1 9.17v6.91");
}

.a83b_cc0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.71 21.88L35.3 33.99v6.91M24 35.72v7.78");
}

.kirvrcbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.16 22.38c2.38 1.5 3.81 3.43 3.81 5.55c0 4.73-7.15 8.56-16 8.56S8 32.66 8 27.93s7.15-8.56 16-8.56a29 29 0 0 1 4 .27");
}

.q1a9arbhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.51 14.01L21.6 7.68m-4.63-1.91l4.74 6.12m4.54 5.81l-3.29-4.28m-.68-8.92l4.11 5.31m1.59 2.21l1.37 1.77");
}

.shqfdzbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40 27.93H8v7c0 4.73 7.15 8.56 16 8.56s16-3.83 16-8.56Zm-16 8.56V19.37");
}

.z_o1-ebmc {
  cx: 32.04px;
  cy: 21.12px;
  r: 4.31px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
