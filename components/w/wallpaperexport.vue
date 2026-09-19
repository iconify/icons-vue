<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_z7vxc_i"/><circle class="r_v_lq5cf"/><circle class="bwzws7bmc"/><circle class="k94bxob-u"/><path class="sx_x9cblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallpaperexport" /></template>
<style>
.bwzws7bmc {
  cx: 39.302px;
  cy: 9.515px;
  r: 2.961px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k94bxob-u {
  cx: 39.539px;
  cy: 29.064px;
  r: 2.961px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_v_lq5cf {
  cx: 22.835px;
  cy: 19.193px;
  r: 2.961px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sx_x9cblb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.746 11.01l-11.467 6.51m.031 3.301l11.82 6.52m-27.942 7.81h17.484l-3.48-6.35l-3.17 4.815l-5.283-8.272z");
}

.w_z7vxc_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 22.887V9.457c0-.656.528-1.185 1.185-1.185h9.223m3.26 0H29.19c.656 0 1.184.529 1.184 1.185v30.806c0 .656-.528 1.184-1.184 1.184h-9.843m-3.439 0H6.685A1.18 1.18 0 0 1 5.5 40.263V27.314");
}

</style>
