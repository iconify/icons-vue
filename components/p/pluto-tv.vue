<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vl09ni-8w"/><path class="h9udect5g"/><circle class="x202kk9_c"/><path class="pw3b1o3pf"/><path class="keh_9qf6n"/><path class="q-brd7byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pluto-tv" /></template>
<style>
.h9udect5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.559 29.857h5.242l2.235 5.923l2.235-5.923");
}

.keh_9qf6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.129 31.869a10.08 10.08 0 0 1 7.281-9.682a10.085 10.085 0 1 0 0 19.363a10.08 10.08 0 0 1-7.281-9.681");
}

.pw3b1o3pf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.33 31.869a10.08 10.08 0 0 1 7.282-9.682a10.085 10.085 0 1 0 0 19.363a10.08 10.08 0 0 1-7.281-9.681");
}

.q-brd7byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.724 31.869a10.08 10.08 0 0 1 7.281-9.682a10.085 10.085 0 1 0 0 19.363a10.08 10.08 0 0 1-7.28-9.681");
}

.vl09ni-8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.42 14.987a2.24 2.24 0 0 1-2.235-2.235v-1.453a2.24 2.24 0 0 1 2.235-2.235h0a2.24 2.24 0 0 1 2.235 2.235v1.453a2.24 2.24 0 0 1-2.235 2.235M21.34 9.064v3.688a2.24 2.24 0 0 0 2.235 2.235h0a2.24 2.24 0 0 0 2.235-2.235V9.064m0 3.688v2.235m3.539-7.823v7.823M28.12 9.064h2.347M18.189 6.047v7.823a1.056 1.056 0 0 0 .99 1.118a1 1 0 0 0 .127 0h.335m-8.273-2.236a2.24 2.24 0 0 0 2.235 2.235h0a2.24 2.24 0 0 0 2.235-2.235v-1.453a2.24 2.24 0 0 0-2.235-2.235h0a2.24 2.24 0 0 0-2.235 2.235m0-2.235v8.941m17.421 9.952v6.117a1.706 1.706 0 0 0 1.706 1.706h0");
}

.x202kk9_c {
  cx: 32.415px;
  cy: 31.869px;
  r: 10.085px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
