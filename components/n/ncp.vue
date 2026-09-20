<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="px9_c_cmp"/><rect class="pgz_txbqx"/><rect class="b1wa3ebnm"/><path class="u2lq3cbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ncp" /></template>
<style>
.b1wa3ebnm {
  width: 13px;
  height: 13px;
  x: 30.904px;
  y: 16.659px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.pgz_txbqx {
  width: 13px;
  height: 13px;
  x: 17.904px;
  y: 16.659px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.px9_c_cmp {
  width: 13px;
  height: 13px;
  x: 4.904px;
  y: 16.659px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.u2lq3cbet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.754 27.159v-8h2.62c1.48 0 2.68 1.203 2.68 2.686s-1.2 2.687-2.68 2.687h-2.62m-26 2.627v-8l5.3 8v-8m12.596 5.317v.033a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 1 1 5.3 0v.033");
}

</style>
