<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="npq1qrb1r"/><path class="j0bvh7bak"/><path class="al4drsh-j"/><path class="y6hnjzb2j"/><path class="lts-34brv"/><path class="x30j7mhjh"/><path class="v9oc75b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pasha-bank" /></template>
<style>
.al4drsh-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.203 16.268v4.53h12v-3.095");
}

.j0bvh7bak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.797 16.268L24 19.471l8.485-8.485l-2.188-2.189");
}

.lts-34brv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.203 31.732L24 28.529l-8.485 8.486l2.188 2.188m3.094-7.471v-4.53h-12v3.095");
}

.npq1qrb1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l6.297 6.297h8.906v8.906L45.5 24l-6.297 6.297v8.906h-8.906L24 45.5l-6.297-6.297H8.797v-8.906L2.5 24l6.297-6.297V8.797h8.906z");
}

.v9oc75b9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.268 20.797h4.53v-12h-3.095");
}

.x30j7mhjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.268 27.203L19.471 24l-8.485-8.485l-2.189 2.188");
}

.y6hnjzb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.732 20.797L28.529 24l8.486 8.485l2.188-2.188m-7.471-3.094h-4.53v12h3.095");
}

</style>
