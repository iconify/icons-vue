<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zeevng8uq"/><path class="yte8c8f8z"/><rect class="s5szhrbfv"/><rect class="i9_9scbso"/><path class="ssn0ocdmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:turns-of-war" /></template>
<style>
.i9_9scbso {
  width: 2.603px;
  height: 2.603px;
  x: 8.965px;
  y: 22.704px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.38px;
  ry: 0.38px;
}

.s5szhrbfv {
  width: 2.907px;
  height: 2.907px;
  x: 33.197px;
  y: 17.535px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.38px;
  ry: 0.38px;
}

.ssn0ocdmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.57 11.07h5.04m-11.736 4.54h18.101M6.316 24.005H26.31M13.394 20.3v7.638m1.674-1.268h8.695m4.601-.998h-2.851l-.077 4.54h3.004m-3.562 2.862h4.12m-4.67 4.254h4.622m-14.949-4.254h4.546m-4.608 4.254h4.621M13.394 15.72v2.511m12.882 1.445v-4.067");
}

.yte8c8f8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.975 14.214v2.865h-2.699v5.194h2.674v7.332m-2.674-10.616h9.038");
}

.zeevng8uq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.817 42.5V31.756h5.244v10.566h7.74v-4.965H28.95v-8.401h10.692v-2.444h2.75V13.565h-15.83V7.948h-2.664V5.5h-7.813v2.808h-2.394v5.437h2.826h-5.643v2.66h-2.47v4.865H5.608v5.471h5.367v2.495h2.623v13.261z");
}

</style>
