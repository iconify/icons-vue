<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wjpgebbbz"/><path class="hx0qswb7f"/><circle class="frfp4zbmz"/><circle class="wijpodbbu"/><circle class="ybrx6c_lo"/><circle class="nbv7jflcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nordic-noodle" /></template>
<style>
.frfp4zbmz {
  cx: 23.76px;
  cy: 13.72px;
  r: 0.75px;
  fill: currentColor;
}

.hx0qswb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.61 16.73l-3.92 3.92c-1.2 1.2-3.14 1.2-4.34 0h0c-1.2-1.2-1.2-3.14 0-4.34l3.92-3.92");
}

.nbv7jflcx {
  cx: 13.72px;
  cy: 24.24px;
  r: 0.75px;
  fill: currentColor;
}

.wijpodbbu {
  cx: 34.28px;
  cy: 23.76px;
  r: 0.75px;
  fill: currentColor;
}

.wjpgebbbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.75 34.25v-20.5L24 3.5L6.25 13.75v20.5L24 44.5zm-8.85-.86L14.61 15.1m.28 18.01l18.55-18.55");
}

.ybrx6c_lo {
  cx: 24.24px;
  cy: 34.28px;
  r: 0.75px;
  fill: currentColor;
}

</style>
