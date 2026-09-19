<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xun798bjs"/><ellipse class="nz3nk3bcb"/><ellipse class="ohi-n8bug"/><path class="iqlwpbc5h"/><ellipse class="set-aobqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vidya-music" /></template>
<style>
.iqlwpbc5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.552 24.514h-2.93V31.8");
}

.nz3nk3bcb {
  cx: 29.187px;
  cy: 17.41px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.403px;
  ry: 1.374px;
}

.ohi-n8bug {
  cx: 34.686px;
  cy: 28.845px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.814px;
  ry: 8.748px;
}

.set-aobqz {
  cx: 33.219px;
  cy: 31.801px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.403px;
  ry: 1.374px;
}

.xun798bjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.648 21.47l-.967-6.575a5.25 5.25 0 0 0-5.192-4.487H12.373a5.25 5.25 0 0 0-5.192 4.487L4.527 32.958a2.54 2.54 0 0 0 2.513 2.908h.687a4.23 4.23 0 0 0 2.904-1.154l3.781-3.572a4.23 4.23 0 0 1 2.904-1.154l8.256.001m-9.778-13.951v8.207M11.69 20.14h8.208");
}

</style>
