<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xt5gxplky"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pebbledialer" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.xt5gxplky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.87 28.1a40 40 0 0 1-4.1-.72a2 2 0 0 0-2 .39c-.34.34-1.33 1.33-2.37 2.33a18.6 18.6 0 0 1-8.51-8.5c1-1 2-2 2.34-2.37a2 2 0 0 0 .37-2c-.3-1.35-.55-2.72-.72-4.1A1.33 1.33 0 0 0 18.42 12H12.9a1 1 0 0 0-.88.91c-.39 5 2.42 10.35 3 11.36q.035.078.08.15a23.26 23.26 0 0 0 8.45 8.44l.3.16c1.27.69 6.42 3.31 11.25 2.93a1 1 0 0 0 .91-.88v-5.46a1.33 1.33 0 0 0-1.124-1.508z");
}

</style>
