<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(135 38.98 38.98)" class="w5cajab4t"/><rect transform="rotate(135 32.055 32.055)" class="gqusc3bgg"/><path class="xgvpbpbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soul-knight-prequel" /></template>
<style>
.gqusc3bgg {
  width: 15.593px;
  height: 6.119px;
  x: 24.258px;
  y: 28.995px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.763px;
  ry: 1.763px;
}

.w5cajab4t {
  width: 7.199px;
  height: 6.47px;
  x: 35.381px;
  y: 35.745px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.17px;
  ry: 3.17px;
}

.xgvpbpbdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 5.5l24.391 24.391m8.018 5.859l-1.915-3.303m-9.494.835L14.408 23.41A24.28 24.28 0 0 1 5.5 5.5h0s0 0 0 0a24.28 24.28 0 0 1 17.91 8.908L33.281 26.5m2.469 11.409l-3.303-1.915");
}

</style>
