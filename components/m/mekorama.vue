<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h22js-b7e"/><path class="yz4hidb_v"/><path class="wv1wtebns"/><circle class="ocqgu4bsl"/><path class="usrdvaccp"/><circle class="y_e8ueb0d"/><path class="req5mqb4z"/><circle class="ut8a8odsf"/><path class="e5779qb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mekorama" /></template>
<style>
.e5779qb7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.26 27.963l7.26 5.165v5.186L28.149 43.5v-5.186L24 36.24l-4.149 2.074V43.5L9.48 38.314v-5.186l7.26-5.207ZM9.48 33.128l10.371 5.186m8.298 0l10.372-5.186M19.851 43.5h8.298");
}

.h22js-b7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.888 25.868h6.224l5.186-1.556V13.94l-5.186 1.556h-6.224l-5.186-1.556v10.372Z");
}

.ocqgu4bsl {
  cx: 24px;
  cy: 11.347px;
  r: 3.63px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.req5mqb4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.463 20.637h-2.35m2.35 0a1.424 1.424 0 0 1 0 2.849h-2.35v-5.697h2.35a1.424 1.424 0 0 1 0 2.848");
}

.usrdvaccp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.333 25.66l.518 4.356s-2.303.185-2.593 1.556c-.273 1.293 5.47 1.25 5.186 0c-.334-1.474-2.593-1.556-2.593-1.556m8.816-4.356l-.518 6.43s-2.304.186-2.593 1.556c-.273 1.293 5.469 1.25 5.186 0c-.334-1.474-2.593-1.555-2.593-1.555M15.703 14.977l-2.075 7.26m18.67-7.26l2.592 5.705");
}

.ut8a8odsf {
  cx: 13.206px;
  cy: 23.374px;
  r: 1.037px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wv1wtebns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.16 14.613a6.742 6.742 0 1 1 11.677 0");
}

.y_e8ueb0d {
  cx: 35.316px;
  cy: 21.585px;
  r: 1.037px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yz4hidb_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.703 13.94v-1.556l1.555-.518m13.484 0zl1.556.518v1.556");
}

</style>
