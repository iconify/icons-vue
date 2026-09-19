<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="r-bcoibzn"/><path class="nsebiwbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oney" /></template>
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

.nsebiwbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 20.858v4.03a2.44 2.44 0 0 1-2.442 2.443h0a2.44 2.44 0 0 1-2.443-2.442v-4.03m-13.964 6.472v-4.03a2.44 2.44 0 0 1 2.443-2.443h0a2.44 2.44 0 0 1 2.442 2.443v4.03m6.71-1.233a2.44 2.44 0 0 1-2.122 1.233h0a2.44 2.44 0 0 1-2.443-2.442V23.3a2.44 2.44 0 0 1 2.443-2.443h0a2.44 2.44 0 0 1 2.442 2.443v.794h-4.885M11 23.3a2.442 2.442 0 1 1 4.885 0v1.588a2.442 2.442 0 1 1-4.885 0z");
}

.r-bcoibzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 24.889v3.297a2.44 2.44 0 0 1-2.442 2.442h0a2.44 2.44 0 0 1-1.728-.715");
}

</style>
