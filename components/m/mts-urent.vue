<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nrl0bmblg"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mts-urent" /></template>
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

.nrl0bmblg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.893 15.995a1.506 1.506 0 1 1-1.508-1.508c.833 0 1.508.673 1.508 1.504zm7.245 2.245a1.506 1.506 0 1 1-1.508-1.508c.833 0 1.508.674 1.508 1.504zm5.095 2.43v9.26a3.575 3.575 0 0 1-3.568 3.583H17.358a3.575 3.575 0 0 1-3.59-3.56v-9.279");
}

</style>
