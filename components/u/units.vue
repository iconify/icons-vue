<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="e-tu586dw"/><circle class="kapemijum"/><path class="yujps5_id"/><path class="pukmuvb6b"/><path class="xlxdjkbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:units" /></template>
<style>
.e-tu586dw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.004 34.3a2.625 2.625 0 1 1 5.25 0v4.2m-5.25-6.826V38.5m5.251-4.2a2.625 2.625 0 1 1 5.25 0v4.2");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.kapemijum {
  cx: 9.514px;
  cy: 10.391px;
  r: 0.75px;
  fill: currentColor;
}

.pukmuvb6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.023 35.037h-3.017a4.492 4.492 0 0 1 0-8.984h20.008a4.492 4.492 0 0 0 0-8.984H20.822");
}

.xlxdjkbvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.321 33.335l1.702 1.702l-1.702 1.702m7.204-17.967l-1.703-1.702l1.703-1.703");
}

.yujps5_id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.514 13.607v6.957m15.391 16.614A2.625 2.625 0 0 1 20 35.875v-1.707a2.624 2.624 0 0 1 4.903-1.308m-7.039-12.296v-4.332a2.625 2.625 0 1 0-5.25 0v4.332m-.001-4.332v-2.625");
}

</style>
