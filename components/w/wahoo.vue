<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qkulsubim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wahoo" /></template>
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

.qkulsubim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.975 22.7c1.108 0 2 .892 2 2V26c0 1.108-.892 2-2 2s-2-.892-2-2v-1.3c0-1.108.892-2 2-2m5.675 0c1.108 0 2 .892 2 2V26c0 1.108-.892 2-2 2s-2-.892-2-2v-1.3c0-1.108.892-2 2-2M23.3 20v8m0-3.3a2 2 0 1 1 4 0V28m-5.675-2a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3m-12.275 0L11 28l1.65-5.3L14.3 28l1.65-5.3");
}

</style>
