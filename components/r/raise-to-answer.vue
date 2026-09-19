<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ckbl4zbyn"/><path class="na009v5xi"/><path class="j28d_t56x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:raise-to-answer" /></template>
<style>
.ckbl4zbyn {
  cx: 29.426px;
  cy: 16.482px;
  r: 10.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j28d_t56x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.901 41.868v-6.469l-6.925 1.727c-5.08 1.267-5.498-4.578-2.944-7.606l9.254-10.975m4.054-4.973l-5.175 1.725l4.168 10.764l4.497-1.499");
}

.na009v5xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 41.868V31.95a3.88 3.88 0 0 0-3.45-3.45H18.488l-6.9 2.587l6.103-6.52");
}

</style>
