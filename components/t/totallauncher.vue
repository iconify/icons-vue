<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9c257bcg"/><path class="n-xr1z3nu"/><path class="gf0nckbah"/><path class="qjrhj9bao"/><path class="p4qjq5qcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:totallauncher" /></template>
<style>
.gf0nckbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.608 16.762a2.51 2.51 0 0 1 2.516-2.518h15.384a2.51 2.51 0 0 1 2.516 2.518v15.396a2.51 2.51 0 0 1-2.516 2.518H18.124a2.51 2.51 0 0 1-2.516-2.518V24.9");
}

.n-xr1z3nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.685 18.963h21.977a2.18 2.18 0 0 1 2.185 2.187v1.546a2.18 2.18 0 0 1-2.185 2.187H6.685A2.18 2.18 0 0 1 4.5 22.696V21.15a2.18 2.18 0 0 1 2.185-2.187");
}

.p4qjq5qcz {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 8.8;
  d: path("M15.608 16.762v1.92");
}

.qjrhj9bao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.354 34.78v4.384a2.18 2.18 0 0 1-2.185 2.187h-10.19a2.18 2.18 0 0 1-2.186-2.187V25.241");
}

.v9c257bcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.858 18.803V8.836a2.18 2.18 0 0 1 2.185-2.187h30.272A2.18 2.18 0 0 1 43.5 8.836V20.15a2.18 2.18 0 0 1-2.185 2.187H36.34");
}

</style>
