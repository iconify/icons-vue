<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="iocb4ubvz"/><rect class="l90667o_y"/><path class="ile1t-bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xos-launcher" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ile1t-bam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.427 18.32L13.963 24l4.464 5.68M9.5 18.32l2.764 3.518m0 4.324L9.5 29.68");
}

.iocb4ubvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.2 28.435c.696.907 1.57 1.245 2.785 1.245h1.681a2.834 2.834 0 0 0 2.834-2.834v-.012A2.834 2.834 0 0 0 35.666 24h-1.855a2.837 2.837 0 0 1-2.837-2.837h0a2.843 2.843 0 0 1 2.843-2.843h1.673c1.215 0 2.088.338 2.785 1.245");
}

.l90667o_y {
  width: 7.526px;
  height: 11.359px;
  x: 21.16px;
  y: 18.32px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.763px;
  ry: 3.763px;
}

</style>
