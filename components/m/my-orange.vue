<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bnm6s56tr"/><path class="gvy-6tbyu"/><rect class="gkj_7cbau"/><circle class="vcy2s9bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-orange" /></template>
<style>
.bnm6s56tr {
  cx: 23.124px;
  cy: 11.779px;
  r: 7.279px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gkj_7cbau {
  width: 10.211px;
  height: 17.605px;
  x: 26.777px;
  y: 25.895px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.673px;
  ry: 1.673px;
}

.gvy-6tbyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.1 23.693s-1.387-2.885-4.492-4.176c0 0-6.085 5.237-13.023 0c0 0-5.346 2.385-5.573 8.186V38.11s.333 3.555 3.98 3.81l9.612-.057");
}

.vcy2s9bez {
  cx: 31.882px;
  cy: 41.14px;
  r: 0.75px;
  fill: currentColor;
}

</style>
