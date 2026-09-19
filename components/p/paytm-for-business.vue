<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w2yum2bag"/><path class="qkqi4yb6l"/><circle class="it5im0gms"/><path class="ja-y9mbes"/><path class="ohhfn9bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paytm-for-business" /></template>
<style>
.it5im0gms {
  cx: 38.5px;
  cy: 38.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ja-y9mbes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.529 38.433a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.301");
}

.ohhfn9bfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 32.69V9.5c0-2.2-1.8-4-4-4h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h23.305");
}

.qkqi4yb6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.648 18.458v3.3a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-3.3m-1.906 3.064a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2m0 3.3v-5.3");
}

.w2yum2bag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 32.5h29.284M5.5 29.467h37m-10.943-5.934v-7.991l4 8l4-7.988v7.988m-31.424 0v-8h2.619a2.687 2.687 0 0 1 0 5.374h-2.62m16.516-5.374h5.3m-2.65 8v-8m-2.65 6.216v2.7a2 2 0 0 1-2 2h0c-.53 0-1.04-.21-1.414-.586");
}

</style>
