<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="sc7ojwo4a"/><path class="qt5rbubty"/><circle class="f_s6jsb0m"/><circle class="zp15_1bxm"/><path class="gzbav5b4d"/><circle class="zneg3ccpg"/><circle class="n0knn-bmr"/><circle class="igv24mjaw"/><circle class="f15ro6b1w"/><path class="c7jt3et0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tooly" /></template>
<style>
.c7jt3et0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.821 6.342a.821.821 0 1 1-1.642 0a.821.821 0 0 1 1.642 0");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f_s6jsb0m {
  cx: 18.048px;
  cy: 26.136px;
  r: 3.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f15ro6b1w {
  cx: 30.419px;
  cy: 15.843px;
  r: 0.75px;
  fill: currentColor;
}

.gzbav5b4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.082v-5.92m4.106 8.681h-8.211");
}

.igv24mjaw {
  cx: 29.952px;
  cy: 26.179px;
  r: 0.75px;
  fill: currentColor;
}

.n0knn-bmr {
  cx: 18.048px;
  cy: 26.179px;
  r: 0.75px;
  fill: currentColor;
}

.qt5rbubty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.042 18.605H13.958a2 2 0 0 0-2 2v11.148a2 2 0 0 0 2 2h20.084a2 2 0 0 0 2-2V20.605a2 2 0 0 0-2-2M27.75 39.11c-1.121 1.163-2.422 1.78-3.75 1.78s-2.629-.617-3.75-1.78");
}

.sc7ojwo4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 38.9V15.082a2 2 0 0 0-2-2h-27a2 2 0 0 0-2 2V38.9");
}

.zneg3ccpg {
  cx: 17.593px;
  cy: 15.843px;
  r: 0.75px;
  fill: currentColor;
}

.zp15_1bxm {
  cx: 29.952px;
  cy: 26.136px;
  r: 3.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
