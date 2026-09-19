<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="t93su45bh"/><circle class="tba3vy_ru"/><circle class="w13-tn5qs"/><circle class="afkxjabcu"/><path class="h8zkhpdpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tracker-detect" /></template>
<style>
.afkxjabcu {
  cx: 29.797px;
  cy: 31.143px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.h8zkhpdpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.33 10.484l1.767-1.792M24 24l10.877-11.028");
}

.t93su45bh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.316 22.289A12.8 12.8 0 0 1 24 11.201c7.069 0 12.799 5.73 12.799 12.799h0c0 7.069-5.73 12.799-12.799 12.799h0a12.8 12.8 0 0 1-12.68-11.053");
}

.tba3vy_ru {
  cx: 11.201px;
  cy: 24px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w13-tn5qs {
  cx: 36.043px;
  cy: 11.67px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
