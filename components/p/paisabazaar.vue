<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cftpx5brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paisabazaar" /></template>
<style>
.cftpx5brm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.218 22.481c0-2.58 2.07-4.673 4.622-4.673s4.622 2.092 4.622 4.673v3.038c0 2.58-2.07 4.673-4.622 4.673s-4.622-2.093-4.622-4.673m0 4.673V11.5m-11.68 14.019c0 2.58 2.07 4.673 4.622 4.673s4.622-2.092 4.622-4.673V22.48c0-2.58-2.07-4.673-4.622-4.673s-4.622 2.093-4.622 4.673m0-4.672V36.5");
}

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

</style>
