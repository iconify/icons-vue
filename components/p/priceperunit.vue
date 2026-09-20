<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o9c2z5bkz"/><rect class="txpskfbbv"/><path class="g89nyhbwv"/><circle class="z5a5zmbja"/><circle class="evb1sn1rc"/><path class="zf-4-ialp"/><path class="j9rwh4bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:priceperunit" /></template>
<style>
.evb1sn1rc {
  cx: 14px;
  cy: 15.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g89nyhbwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.69 5.5A3.19 3.19 0 0 1 5.5 8.69m37 0a3.19 3.19 0 0 1-3.19-3.19m-30.62 20a3.19 3.19 0 0 0-3.19-3.19m37 0a3.19 3.19 0 0 0-3.19 3.19");
}

.j9rwh4bau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.88 34.35H12.12a1 1 0 0 0-1 .75l-1.89 7.4h29.54l-1.92-7.4a1 1 0 0 0-.97-.75");
}

.o9c2z5bkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.51 18.62a2.23 2.23 0 0 0 2 .88h1.18a2 2 0 0 0 2-2a2 2 0 0 0-2-2h-1.3a2 2 0 0 1-2-2a2 2 0 0 1 2-2h1.18a2.23 2.23 0 0 1 2 .88M24 11.5v-1m0 10v-1");
}

.txpskfbbv {
  width: 37px;
  height: 20px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.z5a5zmbja {
  cx: 34px;
  cy: 15.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zf-4-ialp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.32 25.5H8.68a1 1 0 0 0-.91 1.43l1.1 2.31a1 1 0 0 0 .9.57h28.46a1 1 0 0 0 .9-.57l1.1-2.31a1 1 0 0 0-.91-1.43m-22.93 4.31H31.6v4.54H16.39z");
}

</style>
