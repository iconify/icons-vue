<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="r_qp4nb2c"/><circle class="oe-w_fb8v"/><circle class="t_mfswbem"/><circle class="x-6tffbaz"/><path class="zwyjdvbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobildeniz" /></template>
<style>
.oe-w_fb8v {
  cx: 24px;
  cy: 24px;
  r: 2.343px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_qp4nb2c {
  cx: 24px;
  cy: 24px;
  r: 5.074px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t_mfswbem {
  cx: 24px;
  cy: 24px;
  r: 11.037px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x-6tffbaz {
  cx: 24px;
  cy: 24px;
  r: 14.076px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zwyjdvbxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.131v5.634m1.5-8.951v-5.94c0-.83-.822-1.374-1.5-1.374s-1.5.544-1.5 1.374V9.85m9.186 6.465l-3.984 3.983m7.39-5.268l4.2-4.2c.587-.587.39-1.553-.09-2.033s-1.444-.676-2.032-.089l-4.224 4.225m-1.261 18.753l-3.983-3.984m5.268 7.39l4.2 4.2c.588.587 1.553.39 2.033-.09s.676-1.444.089-2.032l-4.225-4.224M13.131 24h5.634m-8.951-1.5h-5.94c-.83 0-1.374.822-1.374 1.5s.544 1.5 1.374 1.5H9.85M34.869 24h-5.634m8.952 1.5h5.939c.83 0 1.374-.822 1.374-1.5s-.544-1.5-1.374-1.5H38.15m-21.835-6.186l3.983 3.984m-5.268-7.39l-4.2-4.2c-.587-.587-1.553-.39-2.033.09s-.676 1.444-.089 2.032l4.225 4.224m3.381 16.631l3.984-3.983m-7.39 5.268l-4.2 4.2c-.587.588-.39 1.553.09 2.033s1.444.676 2.032.089l4.224-4.225M24 34.869v-5.634m-1.5 8.952v5.939c0 .83.822 1.374 1.5 1.374s1.5-.544 1.5-1.374V38.15");
}

</style>
