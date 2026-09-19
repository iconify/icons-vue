<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ivkffdcvn"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quick-settings" /></template>
<style>
.ivkffdcvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.61 12.98l4.224 4.224l-3.637 3.637l-4.212-4.212a6.58 6.58 0 0 0 1.435 7.104a6.58 6.58 0 0 0 7.11 1.44L31.855 35.5l3.639-3.636l-10.332-10.332a6.58 6.58 0 0 0-1.436-7.105a6.58 6.58 0 0 0-7.118-1.447Z");
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
