<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="j2fl0eboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:red" /></template>
<style>
.j2fl0eboi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.4 23.503a3.475 3.475 0 0 1 3.476-3.475h0m-3.476 0v9.21m13.139-1.754a3.47 3.47 0 0 1-3.02 1.754h0a3.475 3.475 0 0 1-3.476-3.475v-2.26a3.475 3.475 0 0 1 3.476-3.475h0a3.475 3.475 0 0 1 3.475 3.475v1.13h-6.95m17.61-1.13a3.475 3.475 0 0 0-3.476-3.475h0a3.475 3.475 0 0 0-3.475 3.475v2.26a3.475 3.475 0 0 0 3.475 3.475h0a3.475 3.475 0 0 0 3.476-3.475m0 3.475V15.336");
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
