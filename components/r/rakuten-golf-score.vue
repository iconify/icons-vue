<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fy2nheyvk"/><circle class="hp6wstbjf"/><path class="o2fevpbbi"/><circle class="e445wwg9c"/><circle class="odv9umhpc"/><circle class="mxr-s5neo"/><circle class="e5w1q3bub"/><circle class="j-aelmdcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-golf-score" /></template>
<style>
.e445wwg9c {
  cx: 13.594px;
  cy: 26.947px;
  r: 0.75px;
  fill: currentColor;
}

.e5w1q3bub {
  cx: 19.363px;
  cy: 29.373px;
  r: 0.75px;
  fill: currentColor;
}

.fy2nheyvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.381 22.627v-8H24c1.48 0 2.681 1.203 2.681 2.687S25.481 20 24 20h-2.619m2.62 0l2.62 2.625m-7.766 1.653l10.292-.003l-8.302 1.922z");
}

.hp6wstbjf {
  cx: 24px;
  cy: 20px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j-aelmdcn {
  cx: 18.195px;
  cy: 31.799px;
  r: 0.75px;
  fill: currentColor;
}

.mxr-s5neo {
  cx: 17.056px;
  cy: 26.947px;
  r: 0.75px;
  fill: currentColor;
}

.o2fevpbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.396 35.86a17.5 17.5 0 0 1-14.792 0M24 43.5v-6");
}

.odv9umhpc {
  cx: 15.901px;
  cy: 29.373px;
  r: 0.75px;
  fill: currentColor;
}

</style>
