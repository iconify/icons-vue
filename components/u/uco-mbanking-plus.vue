<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f-5wm485e"/><path class="w_gs_2aeb"/><path class="ntjs04b8l"/><path class="tcrten4_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uco-mbanking-plus" /></template>
<style>
.f-5wm485e {
  cx: 24px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ntjs04b8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.533 42.5H37.5l5-5v-27l-5-5h-27l-5 5v27l5 5h9.967");
}

.tcrten4_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.533 42.5V31.355l6.392-7.738l-7.654-8.113");
}

.w_gs_2aeb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.467 42.5V31.355l-6.392-7.738l7.654-8.113");
}

</style>
