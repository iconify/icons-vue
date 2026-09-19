<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ezxsapb_u"/><circle class="anqazfphp"/><circle class="mm0f55bdn"/><circle class="qwtl-b2ln"/><path class="xt57lqbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-workdrive" /></template>
<style>
.anqazfphp {
  cx: 38.766px;
  cy: 22.935px;
  r: 3.084px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ezxsapb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 37.024a2.176 2.176 0 0 1-2.18 2.171H6.673A2.176 2.176 0 0 1 4.5 37.017v-26.04a2.176 2.176 0 0 1 2.18-2.172v.001h9.902c2.257 0 6.225 4.13 8.188 4.238h16.908a1.82 1.82 0 0 1 1.822 1.821Z");
}

.mm0f55bdn {
  cx: 24.193px;
  cy: 28.564px;
  r: 3.084px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qwtl-b2ln {
  cx: 31.48px;
  cy: 25.749px;
  r: 3.084px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xt57lqbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.879 39.195v-2.873a3 3 0 0 1 1.922-2.8l5.07-1.95m.029 7.623v-5.611a3 3 0 0 1 1.922-2.8l5.07-1.95m.294 10.361V30.77a3 3 0 0 1 1.923-2.8l5.07-1.95");
}

</style>
