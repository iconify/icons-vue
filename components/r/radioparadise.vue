<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-19.915 24 23.188)" class="repp7_btm"/><path class="w0-lsqb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:radioparadise" /></template>
<style>
.repp7_btm {
  cx: 24px;
  cy: 23.188px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.943px;
  ry: 15.687px;
}

.w0-lsqb_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.092 26.95a6.21 6.21 0 0 0 7.517 4.487h0a6.21 6.21 0 0 0 4.487-7.517l-.985-3.901a6.21 6.21 0 0 0-7.517-4.487h0a6.21 6.21 0 0 0-4.487 7.517m-1.515-6.003l6.06 24.008m-14.028-20.65a6.37 6.37 0 0 1 4.578-7.73h0m-6.154 1.575l4.176 16.309");
}

</style>
