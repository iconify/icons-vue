<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="w34u-1v-f"/><circle class="na0fenbgn"/><path class="yqcad3bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toeic" /></template>
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

.na0fenbgn {
  cx: 32.449px;
  cy: 20.225px;
  r: 0.75px;
  fill: currentColor;
}

.w34u-1v-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.86 22.675za2 2 0 0 1 2 2v1.3a2 2 0 1 1-4 0v-1.3a2 2 0 0 1 2-2");
}

.yqcad3bsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.499 22.675v5.3m-16.264-6.95v5.95a1 1 0 0 0 1 1h.3m-2.35-5.3h2.1m21.284 4.293a2 2 0 0 1-3.737-.993v-1.3a2 2 0 0 1 3.735-.996m-8.645 3.287a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4M11.261 19.87v1.83h-1.83m1.83 0l-1.294-1.294m2.588 0l-2.588 2.588m1.294.206v.33m1.061-.769l.234.233m.535-1.294h-.33");
}

</style>
