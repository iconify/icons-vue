<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="cpk0fnbgt"/><path class="qr2xplb_y"/><path class="lz27qvnei"/><path class="s0o4oobxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yulu" /></template>
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

.lz27qvnei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.253 16.839a15.5 15.5 0 0 1 27.495.002M24.041 33.5h-.082m.041 12v-8.6");
}

.qr2xplb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.489 19.779a9.5 9.5 0 0 1 17.018-.007m-8.228 13.724a10 10 0 0 1-.557 0");
}

.s0o4oobxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.29 15.475C15.432 16.405 24 25.72 24 36.9c0-11.196 8.591-20.518 19.75-21.429");
}

</style>
