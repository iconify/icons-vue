<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="yc3-mqbma"/><path class="svftkib-r"/><circle class="jvh38tbcm"/><path class="g0jh--wyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trivago" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g0jh--wyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.306 21.575v5.3m-7.307-7v6a.945.945 0 0 0 1 1h.3m-2.3-5.3h2.1m17.9 3.3a2.006 2.006 0 0 1-2 2h0a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2h0a2.006 2.006 0 0 1 2 2m0 3.3v-5.3");
}

.jvh38tbcm {
  cx: 16.306px;
  cy: 19.175px;
  r: 0.75px;
  fill: currentColor;
}

.svftkib-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.003 21.575a2.006 2.006 0 0 1 2 2v1.3a2.006 2.006 0 0 1-2 2h0a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2m5.998 5.3a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2h0a2.006 2.006 0 0 1 2 2v1.3a2.006 2.006 0 0 1-2 2m-25.705-3.299a2.006 2.006 0 0 1 2-2h0m-2 0v5.299");
}

.yc3-mqbma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.313 21.575l-2 5.3l-2-5.3m15.69 0v6a2.006 2.006 0 0 1-2 2h0a1.68 1.68 0 0 1-1.4-.6");
}

</style>
