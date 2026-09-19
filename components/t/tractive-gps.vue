<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="legsbrnue"/><path class="js9ficctf"/><ellipse transform="rotate(-21.333 21.901 16.452)" class="rmz1gweec"/><ellipse transform="rotate(-33.445 18.851 19.63)" class="oq-3qokwu"/><path class="gdv4qqbre"/><ellipse transform="rotate(-68.667 26.098 16.452)" class="xrup87buf"/><ellipse transform="rotate(-56.555 29.149 19.63)" class="sypeluiuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tractive-gps" /></template>
<style>
.gdv4qqbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.63c1.443 0 1.777 1.859 3.158 3.177c.885.844 2.244 1.286 2.244 2.698c0 1.588-1.16 2.32-2.169 2.32s-1.675-.858-3.233-.858s-2.225.858-3.233.858s-2.169-.732-2.169-2.32c0-1.412 1.36-1.854 2.244-2.698c1.381-1.318 1.715-3.178 3.158-3.178");
}

.js9ficctf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.81 21.31C40.81 12.026 33.284 4.5 24 4.5S7.19 12.026 7.19 21.31c0 5.268 2.426 9.966 6.218 13.048L24 43.5l10.592-9.142c3.792-3.082 6.218-7.78 6.218-13.048");
}

.legsbrnue {
  cx: 24px;
  cy: 21.31px;
  r: 10.871px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oq-3qokwu {
  cx: 18.851px;
  cy: 19.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.21px;
  ry: 1.715px;
}

.rmz1gweec {
  cx: 21.901px;
  cy: 16.452px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.21px;
  ry: 1.715px;
}

.sypeluiuq {
  cx: 29.149px;
  cy: 19.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.715px;
  ry: 1.21px;
}

.xrup87buf {
  cx: 26.099px;
  cy: 16.452px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.715px;
  ry: 1.21px;
}

</style>
