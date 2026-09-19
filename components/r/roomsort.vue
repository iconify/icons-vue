<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gfrrus91i"/><path class="xyiipp8fn"/><path class="b-6p6jbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:roomsort" /></template>
<style>
.b-6p6jbjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 14c-2.998.025-5 3-5 4.5m5-4.5V5.5m0 13v3h-12M26 5.5V19");
}

.gfrrus91i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5V27h10.5m4.5-8h3.5M26 19h3.5m11 8h2m-8 0v6m6-6c0 3.503-4.004 6-6 6");
}

.xyiipp8fn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 29.5v-24h37v37H13V39c1.996 0 6-2.497 6-6h-6v-3.5zm12-11h-5");
}

</style>
