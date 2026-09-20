<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="njj8adbkt"/><path class="qxgtxnasp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swish" /></template>
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

.njj8adbkt {
  cx: 27.097px;
  cy: 20.119px;
  r: 0.75px;
  fill: currentColor;
}

.qxgtxnasp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.097 22.821v5.847m7.991-8.825v8.825m0-3.641a2.206 2.206 0 0 1 4.412 0v3.64m-14.534-5.846l-1.82 5.847l-1.82-5.847l-1.821 5.847l-1.82-5.847m-5.418 5.353c.403.339.838.494 1.814.494h.495a1.46 1.46 0 0 0 1.459-1.462a1.46 1.46 0 0 0-1.459-1.462h-.99a1.46 1.46 0 0 1-1.458-1.461a1.46 1.46 0 0 1 1.458-1.462h.495c.977 0 1.412.155 1.815.493m13.45 4.86c.403.339.838.494 1.814.494h.495a1.46 1.46 0 0 0 1.459-1.462a1.46 1.46 0 0 0-1.459-1.462h-.99a1.46 1.46 0 0 1-1.458-1.461a1.46 1.46 0 0 1 1.458-1.462h.495c.977 0 1.412.155 1.815.493M8.5 21.153a1.82 1.82 0 0 0 1.82-1.82a1.82 1.82 0 0 0 1.822 1.82a1.82 1.82 0 0 0-1.821 1.821a1.82 1.82 0 0 0-1.821-1.82");
}

</style>
