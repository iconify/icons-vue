<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tkts3_fmg"/><path class="imh0v6tpj"/><circle class="apj43tb_v"/><path class="nq_y2sbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onet-audio" /></template>
<style>
.apj43tb_v {
  cx: 37.223px;
  cy: 19.296px;
  r: 0.75px;
  fill: currentColor;
}

.imh0v6tpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.306 26.686v-5.182m0 3.226a1.955 1.955 0 1 1-3.91 0v-1.27a1.955 1.955 0 1 1 3.91 0m6.359 1.27v1.956m-3.91-5.182v3.226a1.955 1.955 0 1 0 3.91 0v-3.226m6.171 5.284v-7.82m0 4.594a1.955 1.955 0 0 0-3.91 0v1.271a1.955 1.955 0 0 0 3.91 0");
}

.nq_y2sbte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.223 21.691v5.181m2.367-3.412a1.955 1.955 0 1 1 3.91 0v1.27a1.955 1.955 0 1 1-3.91 0z");
}

.tkts3_fmg {
  cx: 10.194px;
  cy: 24.134px;
  r: 5.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
