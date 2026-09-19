<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="i-6g91b1w"/><path class="r7jcnolis"/><circle class="e_8dj6b9i"/><path class="u2pg2tvel"/><circle class="t5en3db_l"/><circle class="qj-zw-1fm"/><circle class="q8bf4cces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:radarscope" /></template>
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

.e_8dj6b9i {
  cx: 24px;
  cy: 24px;
  r: 4.43px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i-6g91b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.07 14.58a16 16 0 1 0 3.51-3.51");
}

.q8bf4cces {
  cx: 17.07px;
  cy: 30.94px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qj-zw-1fm {
  cx: 30.93px;
  cy: 30.93px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r7jcnolis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.56 29a9.93 9.93 0 1 0-16.56.89M18.13 32a9.93 9.93 0 0 0 10.87.58");
}

.t5en3db_l {
  cx: 12.69px;
  cy: 12.69px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u2pg2tvel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24h43M24 2.5v43");
}

</style>
