<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zonicxb2n"/><circle class="avv6g0yxa"/><circle class="r_bhm9wbj"/><circle class="lzr2sy48n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smsq" /></template>
<style>
.avv6g0yxa {
  cx: 16.959px;
  cy: 24px;
  r: 2.235px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lzr2sy48n {
  cx: 31.041px;
  cy: 24px;
  r: 2.235px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_bhm9wbj {
  cx: 23.888px;
  cy: 24px;
  r: 2.235px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zonicxb2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.877 36.081c-1.526 1.494-.879 5.216.03 8.56l2.395-1.582c.03-1.587-.013-3.001.771-3.726a21.499 21.499 0 1 0-14.27 6.153a4.1 4.1 0 0 1 2.86 1.58l2.785-.705c-1.859-2.925-3.205-5.576-5.816-5.433a16.937 16.937 0 1 1 11.245-4.847");
}

</style>
