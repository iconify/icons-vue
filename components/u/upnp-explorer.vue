<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="v2tmldb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:upnp-explorer" /></template>
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

.v2tmldb6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.598 28.687v-3.865a2.35 2.35 0 0 0-2.343-2.342a2.35 2.35 0 0 0-2.342 2.342m0 3.865v-6.324m6.988 6.295v-9.37h3.045c1.757 0 3.162 1.406 3.162 3.162s-1.405 3.163-3.162 3.163h-3.045m-15.499 3.074v-9.37h3.045c1.757 0 3.163 1.406 3.163 3.163s-1.406 3.162-3.163 3.162h-3.045m-8.51-6.324v6.207c0 1.757 1.405 3.162 3.045 3.162s3.162-1.406 3.162-3.162v-6.207");
}

</style>
