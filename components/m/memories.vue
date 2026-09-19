<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="zt-3-fbzp"/><path class="l1uw_9bmf"/><path class="ueqwbs2rn"/><rect class="zyr_wmtej"/><circle class="mz9blvxwo"/><path class="qwzrobcky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:memories" /></template>
<style>
.l1uw_9bmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.538 9.523l.477.121l.009.003l.003.003l3.005.766a2.7 2.7 0 0 1 1.678 1.264c.352.597.476 1.328.289 2.052L32.82 34.015m-2.992 8.465l.003-.002a2.7 2.7 0 0 0 1.087-1.201m-23.425-3.92a2.72 2.72 0 0 1-.95-2.815l.27-1.054v-.003l.68-2.662M13.32 8.005l.136-.54a2.726 2.726 0 0 1 3.316-1.967l1.443.369l8.373 2.138");
}

.mz9blvxwo {
  cx: 20.157px;
  cy: 22.556px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qwzrobcky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.321 18.808h-4.327l-2.164 3.748l2.164 3.748h4.327l2.164-3.748zm2.164 3.748l2.169 3.758m-12.988-7.506l2.164 3.748m4.327-7.5l-2.163 3.752m4.327 7.496l-2.164 3.752m-2.163-3.752H13.66m8.661-7.496h4.333");
}

.ueqwbs2rn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.014 9.644l.01.003l.003.003M30.41 41.388l-.204.47a2.6 2.6 0 0 1-.374.62l-.004.003a2.72 2.72 0 0 1-3.205.794l-4.317-1.871M37.71 11.68l2.188.947a2.727 2.727 0 0 1 1.42 3.583l-8.497 19.613M18.215 5.867a2.72 2.72 0 0 1 3.443-1.14l7.57 3.278");
}

.zt-3-fbzp {
  width: 25.33px;
  height: 33.399px;
  x: 7.492px;
  y: 8.004px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.725px;
  ry: 2.725px;
}

.zyr_wmtej {
  width: 20.568px;
  height: 23.133px;
  x: 9.873px;
  y: 11.143px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.862px;
  ry: 1.862px;
}

</style>
