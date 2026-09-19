<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yex_g2bpq"/><path class="tq1i92bbt"/><path class="uc7a3fbbo"/><path class="bstvpacux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oandbackupx" /></template>
<style>
.bstvpacux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.84 17l-9.42 3.6L24 17");
}

.tq1i92bbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 25.26L24 32.71l19.5-7.45");
}

.uc7a3fbbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 15.32L24 13L4.5 20.49L24 27.94l19.5-7.45m-10.08-9.96v10.08");
}

.yex_g2bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 30.07L24 37.52l19.5-7.45");
}

</style>
