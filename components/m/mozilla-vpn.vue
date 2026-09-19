<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vw556uh6r"/><circle class="jzu5c5bfq"/><circle class="ks_isabuz"/><circle class="c47iheb2x"/><circle class="ukzzl2_xi"/><circle class="zazsdq7vl"/><circle class="cij13_bgs"/><circle class="tbhm5nwtz"/><circle class="y6bfy2vpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mozilla-vpn" /></template>
<style>
.c47iheb2x {
  cx: 37.621px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cij13_bgs {
  cx: 24px;
  cy: 10.379px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jzu5c5bfq {
  cx: 10.379px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ks_isabuz {
  cx: 10.379px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tbhm5nwtz {
  cx: 24px;
  cy: 37.621px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ukzzl2_xi {
  cx: 37.621px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vw556uh6r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.329 19.05l3.721-3.721m9.9 17.342l3.721-3.721M30.621 24H17.379");
}

.y6bfy2vpm {
  cx: 24px;
  cy: 37.621px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zazsdq7vl {
  cx: 24px;
  cy: 10.379px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
