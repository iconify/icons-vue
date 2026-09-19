<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wjrxhnbeg"/><circle class="mwd4o8a1p"/><circle class="lqq5krwty"/><path class="epcq04pvy"/><path class="v25ccjp1x"/><path class="n6s0q9n_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:model3d" /></template>
<style>
.epcq04pvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.1 16.35l-.2 18.9a19.49 19.49 0 0 1-21.7 0l-.1-18.9");
}

.lqq5krwty {
  cx: 28.9px;
  cy: 12.35px;
  r: 1.1px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.mwd4o8a1p {
  cx: 19.1px;
  cy: 12.35px;
  r: 1.1px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.n6s0q9n_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.6 23.85v6.3l-5.6 3l-5.5-3v-6.3m5.4 2.8v6.4m-13.7.4H8a1.11 1.11 0 0 1-1.1-1.1v-14a1.11 1.11 0 0 1 1.1-1.1h2.1a1.11 1.11 0 0 1 1.1 1.1v14a1 1 0 0 1-1 1.1m29.8 0h-2.1a1.11 1.11 0 0 1-1.1-1.1v-14a1.11 1.11 0 0 1 1.1-1.1H40a1.11 1.11 0 0 1 1.1 1.1v14a1.11 1.11 0 0 1-1.1 1.1");
}

.v25ccjp1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.6 37.35V42a1.58 1.58 0 0 0 1.6 1.6H20a1.58 1.58 0 0 0 1.6-1.6v-3.4m5.5-.25v3.5a1.58 1.58 0 0 0 1.6 1.6h1.8a1.58 1.58 0 0 0 1.6-1.6v-5m-8.2-15.8l-5.5 2.8l5.5 2.8l5.7-2.8Z");
}

.wjrxhnbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.1 16.35c.5-13.2 20.7-14.5 22 0c-5.7 2.5-16.8 2-22 0m5.4-8.9l-2.1-3m13.4 3l2.1-3");
}

</style>
