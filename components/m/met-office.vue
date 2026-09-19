<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="in26lsbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:met-office" /></template>
<style>
.in26lsbdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.228c3.71-.492 9.469-8.096 16.425-7.86c6.96.237 12.106 4.487 20.575 2.95m-37 9.147c5.937 1.095 9.918 1.217 16.425-2.897c8.52-5.387 12.194-2.539 20.575-1.152m-37 8.329c6.76 1.112 14.477 4.834 20.2.452c3.438-2.633 7.412-6.248 16.8-4.501M5.5 33.76c3.7-.29 7.639-1.087 14.404 1.4c11.206 4.115 14.96-3.46 22.596-5.45");
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
