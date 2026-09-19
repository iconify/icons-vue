<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pnac_n1_t"/><path class="o4jgy2k9e"/><path class="ejzowebbc"/><path class="lr1c83bgz"/><path class="l9sh2lw5x"/><path class="cuxufqz5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:resq-club" /></template>
<style>
.cuxufqz5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.797 28.365s7.534-8.966 17.293.863c3.544 3.569 6.939 9.43 11.896 5.613");
}

.ejzowebbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.469 34.13a11.34 11.34 0 1 1 6.007-5.929");
}

.l9sh2lw5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.313 30.28s6.242-7.896 15.38 2.003c3.828 5.138 8.837 8.84 14.467 4.034");
}

.lr1c83bgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.268 31.626s5.17-6.108 12.075 2.745c4.517 5.791 11.134 9.202 17.157 3.882");
}

.o4jgy2k9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.428 36.219a14.058 14.058 0 0 1-16.305-22.47a14.06 14.06 0 0 1 18.179-1.476a14.06 14.06 0 0 1 4.34 17.714");
}

.pnac_n1_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.268 38.09c-7.217 4.1-16.355 2.23-21.382-4.375s-4.394-15.91 1.48-21.773a16.58 16.58 0 0 1 26.11 19.95");
}

</style>
