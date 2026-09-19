<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="e4ymod9lw"/><ellipse class="j1n2odbny"/><path class="o8nw_h1nq"/><path class="k9rw5cd5e"/><ellipse class="jmyq-t9ex"/><path class="yim76xukq"/><ellipse class="fpzt-oblk"/><path class="ry2l5acaq"/></g><path class="el4vs8bak"/><path class="s93izgb7m"/><rect class="g0x3hybeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mein-haushaltsbuch" /></template>
<style>
.e4ymod9lw {
  d: path("M17.337 24c0 1.042 1.64 1.886 3.665 1.886s3.666-.844 3.666-1.886m-7.331 3.037c0 1.042 1.64 1.886 3.665 1.886s3.666-.844 3.666-1.886m-7.331 3.037c0 1.042 1.64 1.886 3.665 1.886s3.666-.844 3.666-1.886");
}

.el4vs8bak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 21.5v-10a6 6 0 0 0-6-6h-25a6 6 0 0 0-6 6v25a6 6 0 0 0 6 6h25a6 6 0 0 0 6-6v-10");
}

.fpzt-oblk {
  cx: 13.671px;
  cy: 26.829px;
  rx: 3.666px;
  ry: 1.886px;
}

.g0x3hybeu {
  width: 10px;
  height: 5px;
  x: 34.5px;
  y: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

.j1n2odbny {
  cx: 28.334px;
  cy: 14.889px;
  rx: 3.666px;
  ry: 1.886px;
}

.jmyq-t9ex {
  cx: 21.002px;
  cy: 20.755px;
  rx: 3.666px;
  ry: 1.886px;
}

.k9rw5cd5e {
  d: path("M24.668 14.889V33.11c0 1.042 1.642 1.886 3.666 1.886S32 34.153 32 33.111V14.89");
}

.o8nw_h1nq {
  d: path("M24.668 17.926c0 1.041 1.642 1.886 3.666 1.886S32 18.967 32 17.926m-7.332 3.037c0 1.041 1.642 1.886 3.666 1.886S32 22.004 32 20.963M24.668 24c0 1.042 1.642 1.886 3.666 1.886S32 25.042 32 24m-7.332 3.037c0 1.042 1.642 1.886 3.666 1.886S32 28.079 32 27.037m-7.332 3.037c0 1.042 1.642 1.886 3.666 1.886S32 31.116 32 30.074");
}

.ry2l5acaq {
  d: path("M10.005 26.829v6.282c0 1.042 1.641 1.886 3.666 1.886s3.666-.844 3.666-1.886V26.83");
}

.s93izgb7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 21.5v-10a6 6 0 0 0-6-6m0 37a6 6 0 0 0 6-6v-10");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yim76xukq {
  d: path("M17.337 20.963V33.11c0 1.042 1.64 1.886 3.665 1.886s3.666-.844 3.666-1.886V20.963M10 30.07c0 1.04 1.641 1.885 3.666 1.885s3.666-.844 3.666-1.886");
}

</style>
