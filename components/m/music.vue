<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v89m_cccs"/><circle class="t9jw750lp"/><circle class="w1qs9fdcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music" /></template>
<style>
.t9jw750lp {
  cx: 11.45px;
  cy: 37.74px;
  r: 5.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v89m_cccs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.31 13.38l-25.1 3.48V7.98l25.1-3.48zm0 0v17.15m-25.1-13.67v20.88");
}

.w1qs9fdcc {
  cx: 36.55px;
  cy: 30.53px;
  r: 5.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
