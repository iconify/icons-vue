<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="b7u-ac86j"/><path class="xwyuwdcxy"/><circle class="alno0ql2t"/><path class="svtt5nbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-iijmio" /></template>
<style>
.alno0ql2t {
  cx: 30.969px;
  cy: 31.553px;
  r: 0.75px;
  fill: currentColor;
}

.b7u-ac86j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 26.251h37m-27.906 3v8m-2.5-8v8m9-8v6a2 2 0 1 1-4 0v-.664m6 .238a1.47 1.47 0 1 1 2.938 0v2.426m-2.938-3.897v3.897");
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

.svtt5nbps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.969 33.354v3.897m2-2.426a1.47 1.47 0 1 1 2.938 0v.956a1.47 1.47 0 1 1-2.938 0zM13.217 22.326V10.749l5.751 11.59l5.751-11.572v11.572m7.376 0l-3.063-7.678m5.751 0l-3.651 10.43a1.73 1.73 0 0 1-1.627 1.16h-.473");
}

.xwyuwdcxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.031 34.825a1.47 1.47 0 1 1 2.938 0v2.426");
}

</style>
