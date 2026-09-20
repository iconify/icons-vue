<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5sn8pxnn"/><path class="xho43sbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saldo" /></template>
<style>
.t5sn8pxnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.454 2.57C37.307 3.817 45.5 13.005 45.5 23.93c0 11.874-9.626 21.5-21.5 21.5a21.5 21.5 0 0 1-9.488-2.207M5.644 12.736A21.5 21.5 0 0 1 21.153 2.62M10.174 40.394a21.5 21.5 0 0 1-6.877-22.262m11.215 25.091l-.002-.001");
}

.xho43sbuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.683 30.495c1.058 1.378 2.385 1.891 4.231 1.891h2.555a4.31 4.31 0 0 0 4.306-4.314a4.31 4.31 0 0 0-4.306-4.315h-2.823a4.31 4.31 0 0 1-4.305-4.315a4.31 4.31 0 0 1 4.305-4.314h2.555c1.846 0 3.173.513 4.232 1.89m-5.375-1.89v-2.165m0 21.463v-2.04");
}

</style>
