<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="m-ff1gbzq"/><path class="j_9pf8bpk"/><path class="nf9e3h8rl"/><path class="t2vmyya8h"/><path class="qv77dmbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:racing-calendar" /></template>
<style>
.j_9pf8bpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 4.5v6m-19-6v6m10.625 15.226c.684 0 1.24 1.097 1.24 2.441c0 1.353-.556 2.45-1.24 2.45s-1.24-1.097-1.24-2.45c0-1.344.557-2.441 1.24-2.441m10.82 0c.683 0 1.24 1.097 1.24 2.441c0 1.353-.557 2.45-1.24 2.45c-.691 0-1.247-1.097-1.247-2.45c0-1.344.556-2.441 1.247-2.441m-18.732 1.772v1.767h-5.124l.015-1.767zm16.335-4.868l4.267-.098v2.641");
}

.m-ff1gbzq {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nf9e3h8rl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.143 24.027H17.25c-5.89-.03-7.98 1.849-7.739 6.642h13.292m3.041-.503l8.124.067");
}

.qv77dmbjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.143 24.027c2.366.828.135 5.471-4.103 4.014l.406-3.72m-4.44-.21c-2.585 1.35-4.517 3.485-6.027 1.892h-5.275m15.562-5.447l-1.788 3.396");
}

.t2vmyya8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.446 24.027c1.488-1.525 4.012-3.389 5.876-3.696l7.19.15q1.932 0 3.043 2.412c1.714 1.518 4.854.894 5.546 5.087c-1.15 1.404.849 1.059-2.346 2.036");
}

</style>
