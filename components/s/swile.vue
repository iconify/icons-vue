<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ejl1n6-ke"/><circle class="saiq40xqt"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swile" /></template>
<style>
.ejl1n6-ke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.948 22.952c-2.562-.633-2.308 3.793-2.851 5.517l-1.68-5.669l-1.68 5.67l-1.784-5.67m10.109 0v5.67m-15.352-.42c.42.314.84.42 1.68.42h.42a1.39 1.39 0 0 0 1.364-1.366a1.39 1.39 0 0 0-1.364-1.364h-.945a1.39 1.39 0 0 1-1.365-1.365c0-.735.63-1.365 1.365-1.365h.42c.945 0 1.364 0 1.68.42m14.403-3.36v7.35c0 .63.42 1.05 1.05 1.05h.315m5.452-1.05c-.315.63-1.05 1.05-1.785 1.05c-1.154 0-2.1-.946-2.1-2.1v-1.365c0-1.155.946-2.1 2.1-2.1s2.1.945 2.1 2.1v.735h-4.2");
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

.saiq40xqt {
  cx: 27.062px;
  cy: 20.281px;
  r: 0.75px;
  fill: currentColor;
}

</style>
