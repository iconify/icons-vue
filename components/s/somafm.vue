<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqe628bwx"/><circle class="ulmoqov5g"/><circle class="lk_47xb0v"/><circle class="mz9mv1brq"/><path class="hb6d7bb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:somafm" /></template>
<style>
.fqe628bwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.233 24.762H42.5v17.766H13.233z");
}

.hb6d7bb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.822 38.86v-5.651m12.888-8.447L16.683 16.95M5.5 14.689l3.371 3.927l.515-3.49l3.332 4.481m6.341-14.136l-1.117 5.053l3.101-1.682l-1.585 5.354");
}

.lk_47xb0v {
  cx: 23.822px;
  cy: 29.681px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mz9mv1brq {
  cx: 18.574px;
  cy: 29.681px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ulmoqov5g {
  cx: 33.795px;
  cy: 33.645px;
  r: 5.215px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
