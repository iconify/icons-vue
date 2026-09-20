<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t_mjdjb3a"/><ellipse transform="rotate(-70 16.528 15.025)" class="qpneybyea"/><ellipse transform="rotate(-20 31.472 15.025)" class="xz-ig9bea"/><path class="pw-7d_02i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:restoid" /></template>
<style>
.pw-7d_02i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.076 9.823l2.63-4.315c1.052-1.82 2.987-.978 1.988.965l-2.105 4.092m-16.665-.742l-2.63-4.315c-1.052-1.82-2.987-.978-1.988.965l2.106 4.092m14.492 13.888a6.976 6.976 0 1 1-7.577-1.522m-.25 1.88l.25-1.88l-1.793-.615");
}

.qpneybyea {
  cx: 16.528px;
  cy: 15.025px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.285px;
  ry: 1.951px;
}

.t_mjdjb3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.732L7.826 12.511S7.776 39.073 24 43.5m0-35.768l16.174 4.779S40.224 39.073 24 43.5");
}

.xz-ig9bea {
  cx: 31.472px;
  cy: 15.025px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.951px;
  ry: 2.285px;
}

</style>
