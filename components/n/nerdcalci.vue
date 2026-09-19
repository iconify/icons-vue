<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="iqipk6buj"/><path class="ly9scblwi"/><path class="i1joc-b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nerdcalci" /></template>
<style>
.i1joc-b7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.68 27.648c-1.901 1.581-3.776 3.303-5.332 5.354m-4.927.36c-2.866-1.133-1.513-3.245-1.237-5.107c-.065-.44-1.322-1.363-2.047-1.372c-1.589-.215-5.582 5.04-4.095 6.682c1.689 1.869 5.337-3.571 6.142-5.31");
}

.iqipk6buj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.577 13.946q1.687 5.974 5.174 7.447");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ly9scblwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.661 14.126c-2.681 2.22-4.657 4.44-6.907 6.66m15.096-5.76c2.572.266 3.935-.176 6.052-.045m-7.132 3.217c2.267.011 3.987-.235 5.827-.18m3.96 2.295q-2.542 5.49-4.095 11.88q4.782-5.94 6.502-3.87c1.657 1.787-3.438 6.768-5.602 5.534M21.19 27.4c1.896 1.941 3.821 4.003 5.603 5.49");
}

</style>
