<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aomxzow-t"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tops" /></template>
<style>
.aomxzow-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.736 20.575c-.667-.476-3.054-.93-4.464-.224c-.94.47-1.495 1.847-.01 2.49c1.243.54 2.358.251 3.809.793c1.517.566.93 2.02-.01 2.49c-1.41.707-4.146.253-4.812-.223m-8.943-2.61a3.273 3.273 0 0 0 3.275 3.271h.002c1.809 0 3.276-1.464 3.276-3.27s-1.467-3.27-3.276-3.27a3.273 3.273 0 0 0-3.277 3.27q0 0 0 0v6.535m-2.867-6.535a3.273 3.273 0 0 1-3.276 3.27h0a3.273 3.273 0 0 1-3.276-3.27h0a3.273 3.273 0 0 1 3.276-3.27h0a3.273 3.273 0 0 1 3.276 3.27M12.2 18.173h4.202m-8.403 0h4.2v8.39");
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
