<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wio-qb3mc"/><circle class="ful73vbzy"/><circle class="qz5oyqsxh"/><path class="rnjeov5ev"/><circle class="tomknv9ug"/><path class="l5btsbcek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uyap-mobil" /></template>
<style>
.ful73vbzy {
  cx: 20.278px;
  cy: 37.567px;
  r: 1.136px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l5btsbcek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.169 13.074c.437.209.79.561 1 .998m1.579-.675a3.74 3.74 0 0 0-1.74-1.77m.412 4.073a2.454 2.454 0 1 1-2.864-2.806m15.863-3.597H8.579m0 0H39.42m-29.065 1.776a1.776 1.776 0 1 1-3.551 0a1.776 1.776 0 0 1 3.551 0m-5.301 8.683l2.848-7.004m1.337-.063l2.91 7.067m-7.649 0s2.311 3.465 4.101 3.465s4.101-3.465 4.101-3.465zm33.145-8.683a1.776 1.776 0 1 0 3.551 0a1.776 1.776 0 0 0-3.551 0m5.301 8.683l-2.849-7.004m-1.336-.063l-2.91 7.067m7.649 0s-2.311 3.465-4.101 3.465s-4.101-3.465-4.101-3.465z");
}

.qz5oyqsxh {
  cx: 27.721px;
  cy: 34.815px;
  r: 1.136px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rnjeov5ev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.169 21.11v11.013");
}

.tomknv9ug {
  cx: 24px;
  cy: 15.303px;
  r: 0.75px;
  fill: currentColor;
}

.wio-qb3mc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.83 21.11v11.862m11.259-16.266l-6.369 2.769v14.204m-7.44 2.271V19.474l-6.37-2.77");
}

</style>
