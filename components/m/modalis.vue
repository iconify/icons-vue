<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e__w1c6_z"/><path class="ha3mxacxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:modalis" /></template>
<style>
.e__w1c6_z {
  cx: 24.353px;
  cy: 24.05px;
  r: 9.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ha3mxacxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 6.81c16.13-.12 16.13-.211 18.147 5.142M42.5 41.19c-16.13.12-16.13.211-18.147-5.142");
}

</style>
