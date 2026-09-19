<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oyao_d1sc"/><circle class="mzf_k7n4u"/><circle class="jx311nbqz"/><circle class="b3uq-1vct"/><circle class="ijsljpbxv"/><circle class="s5d3ukb_m"/><path class="zhke1ilvj"/><circle class="dg09ue1_r"/><circle class="x-u0cy-kt"/><circle class="rk4yr3v-e"/><circle class="bc6cbb6yf"/><circle class="k23ejg-8y"/><circle class="w6t191a6m"/><circle class="d1xshsbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reckoning-skills" /></template>
<style>
.b3uq-1vct {
  cx: 34.274px;
  cy: 34.433px;
  r: 0.75px;
  fill: currentColor;
}

.bc6cbb6yf {
  cx: 37.497px;
  cy: 31.21px;
  r: 0.75px;
  fill: currentColor;
}

.d1xshsbgq {
  cx: 37.497px;
  cy: 37.656px;
  r: 0.75px;
  fill: currentColor;
}

.dg09ue1_r {
  cx: 37.497px;
  cy: 34.433px;
  r: 0.75px;
  fill: currentColor;
}

.ijsljpbxv {
  cx: 31.046px;
  cy: 34.433px;
  r: 0.75px;
  fill: currentColor;
}

.jx311nbqz {
  cx: 14.151px;
  cy: 29.432px;
  r: 0.75px;
  fill: currentColor;
}

.k23ejg-8y {
  cx: 34.274px;
  cy: 37.656px;
  r: 0.75px;
  fill: currentColor;
}

.mzf_k7n4u {
  cx: 14.151px;
  cy: 23.028px;
  r: 0.75px;
  fill: currentColor;
}

.oyao_d1sc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.417 29.67l6.663-6.662m-6.678-.015l5.46 5.46M9.44 26.34h9.422m3.175-12.179h9.423M14.15 9.428v9.466m-4.71-4.733h9.422");
}

.rk4yr3v-e {
  cx: 31.046px;
  cy: 31.21px;
  r: 0.75px;
  fill: currentColor;
}

.s5d3ukb_m {
  cx: 34.274px;
  cy: 34.433px;
  r: 8.067px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w6t191a6m {
  cx: 31.046px;
  cy: 37.656px;
  r: 0.75px;
  fill: currentColor;
}

.x-u0cy-kt {
  cx: 34.274px;
  cy: 31.21px;
  r: 0.75px;
  fill: currentColor;
}

.zhke1ilvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.258 35.079H8.348c-1.49 0-2.69-1.2-2.69-2.69V8.19c0-1.49 1.2-2.689 2.69-2.689H32.55c1.49 0 2.689 1.2 2.689 2.689v18.177");
}

</style>
