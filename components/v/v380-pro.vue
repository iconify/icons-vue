<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zco1r7y-k"/><circle class="bxj_sjz_b"/><circle class="n87vf_zjw"/><path class="hlouh2bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:v380-pro" /></template>
<style>
.bxj_sjz_b {
  cx: 24px;
  cy: 19.297px;
  r: 14.797px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hlouh2bty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.496 33.895v5.276h10.809V43.5h-26.61v-4.329h10.809v-5.276");
}

.n87vf_zjw {
  cx: 24px;
  cy: 16.369px;
  r: 2.282px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zco1r7y-k {
  cx: 24px;
  cy: 19.052px;
  r: 7.91px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
