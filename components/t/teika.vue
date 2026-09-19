<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="su6ok7ywf"/><circle class="d15w8nq-w"/><path class="fi4yvlt-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:teika" /></template>
<style>
.d15w8nq-w {
  cx: 23.417px;
  cy: 19.299px;
  r: 0.75px;
  fill: currentColor;
}

.fi4yvlt-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.417 22.382v6.668m4.173-3.575l3.582 3.567m-5.032-2.124l4.556-4.534m-4.557-3.393v10.066m11.231.025v-6.669m0 4.152a2.517 2.517 0 0 1-2.516 2.517h0a2.517 2.517 0 0 1-2.517-2.517V24.93a2.517 2.517 0 0 1 2.516-2.517h0a2.517 2.517 0 0 1 2.517 2.517");
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

.su6ok7ywf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.63 22.388h2.642m-1.32-2.076v7.486c0 .695.562 1.259 1.257 1.259h.378m6.855-1.257a2.52 2.52 0 0 1-2.186 1.27h0a2.517 2.517 0 0 1-2.517-2.517v-1.636a2.517 2.517 0 0 1 2.517-2.517h0a2.517 2.517 0 0 1 2.516 2.517v.818h-5.033");
}

</style>
