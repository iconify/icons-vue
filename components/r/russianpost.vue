<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmnsg-b3d"/><rect class="z4vvg0u8d"/><path class="k3u_4kbke"/><rect class="svoe1g2mu"/><path class="dl6k3ua2t"/><path class="hzpqnlmob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:russianpost" /></template>
<style>
.dl6k3ua2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.451 15.654v4.391h-2.196a2.46 2.46 0 0 1-2.459-2.46v-1.931m4.655 4.391v2.635m-17.956 0v-7.027h4.655v7.027m23.584-2.327h-3.113m-.772 2.327l2.328-7.027l2.328 7.027");
}

.hzpqnlmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

.k3u_4kbke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.995 32.337v-7.026l-4.655 7.026v-7.026m11.16 7.026v-7.026l-4.655 7.026v-7.026m-5.6-9.658H33.9m-2.327 7.027v-7.027");
}

.nmnsg-b3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 32.337v-7.026h2.3c1.3 0 2.355 1.056 2.355 2.36s-1.054 2.36-2.355 2.36H8.5m17.765-.041v.029a2.328 2.328 0 1 1-4.655 0v-2.371a2.328 2.328 0 1 1 4.655 0v.028");
}

.svoe1g2mu {
  width: 4.655px;
  height: 7.027px;
  x: 16.066px;
  y: 15.653px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.328px;
  ry: 2.328px;
}

.z4vvg0u8d {
  width: 4.655px;
  height: 7.027px;
  x: 14.879px;
  y: 25.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.328px;
  ry: 2.328px;
}

</style>
