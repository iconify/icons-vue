<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xy9xuui9d"/><path class="gmkjf9cem"/><circle class="iu6f4qb4a"/><circle class="c9n55xbzu"/><circle class="t8uvolu-m"/><circle class="a2k0g1bnb"/><path class="trt7t0btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unipatcher" /></template>
<style>
.a2k0g1bnb {
  cx: 33.846px;
  cy: 22.384px;
  r: 1.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c9n55xbzu {
  cx: 31.102px;
  cy: 25.128px;
  r: 1.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gmkjf9cem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.588 21.287a1.355 1.355 0 0 0-1.359 1.359v1.165h-1.165a1.36 1.36 0 0 0 0 2.72h1.165v1.164a1.358 1.358 0 0 0 2.717 0V26.53h1.168a1.36 1.36 0 0 0 0-2.72h-1.168v-1.164a1.355 1.355 0 0 0-1.358-1.359");
}

.iu6f4qb4a {
  cx: 36.59px;
  cy: 25.128px;
  r: 1.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t8uvolu-m {
  cx: 33.846px;
  cy: 27.872px;
  r: 1.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.trt7t0btj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.523s-.79-2.597 1.647-2.545s1.999-2.579 1.999-2.579");
}

.xy9xuui9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.525h5.924s5.248 5.474 10.555 5.053s2.95-11.169-1.887-15.83S27.79 16.524 24 16.524s-9.754-.435-14.592 4.226s-7.193 15.408-1.886 15.829s10.554-5.054 10.554-5.054zm-3.846-4.434h2.545m5.148 0H25.3");
}

</style>
