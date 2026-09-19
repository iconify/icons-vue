<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-21.909 24 24)" class="v3sc3_uzl"/><path class="o7t16riab"/><circle class="w0w76rbwa"/><circle class="ddqf64w3e"/><circle class="in2jwu6pe"/><circle class="avxzzrbaq"/><path class="ndsnwrb4i"/><circle class="niew53-tq"/><circle class="d-5oc754c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vita3k" /></template>
<style>
.avxzzrbaq {
  cx: 37.171px;
  cy: 13.916px;
  r: 0.75px;
  fill: currentColor;
}

.d-5oc754c {
  cx: 38.616px;
  cy: 20.344px;
  r: 1.243px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ddqf64w3e {
  cx: 36.239px;
  cy: 16.1px;
  r: 0.75px;
  fill: currentColor;
}

.in2jwu6pe {
  cx: 38.423px;
  cy: 17.031px;
  r: 0.75px;
  fill: currentColor;
}

.ndsnwrb4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.479 28.086l.614-.246m2.022-.814l.614-.247m-2.279-.971l.247.614m.813 2.022l.247.614");
}

.niew53-tq {
  cx: 10.813px;
  cy: 31.526px;
  r: 1.243px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o7t16riab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.327 21.647l21.91-8.811l5.13 12.756l-21.91 8.811z");
}

.v3sc3_uzl {
  width: 39.77px;
  height: 18.081px;
  x: 4.115px;
  y: 14.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.708px;
  ry: 7.708px;
}

.w0w76rbwa {
  cx: 39.355px;
  cy: 14.847px;
  r: 0.75px;
  fill: currentColor;
}

</style>
