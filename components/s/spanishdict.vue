<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cyoc3kexp"/><path class="n015du51j"/><circle class="y1_ij-bed"/><path class="t1k8oobja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spanishdict" /></template>
<style>
.cyoc3kexp {
  cx: 31.855px;
  cy: 31.943px;
  r: 4.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n015du51j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.253 4.5h-8.796l1.245 19.269h6.306z");
}

.t1k8oobja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.747 43.5h8.796l-1.245-19.269h-6.306z");
}

.y1_ij-bed {
  cx: 16.145px;
  cy: 16.057px;
  r: 4.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
