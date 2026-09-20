<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="owgvyex0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:red" /></template>
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

.owgvyex0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.4 23.503a3.475 3.475 0 0 1 3.476-3.475m-3.476 0v9.21m13.139-1.754a3.475 3.475 0 0 1-6.495-1.722v-2.259a3.475 3.475 0 1 1 6.951 0v1.13h-6.952m17.611-1.13a3.475 3.475 0 1 0-6.951 0v2.26a3.475 3.475 0 1 0 6.951 0m0 3.475V15.336");
}

</style>
