<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ll92nnquh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tgv" /></template>
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

.ll92nnquh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 18.93h6.718m-3.359 10.14V18.93m23.641 0l-3.36 10.141l-3.358-10.141m-3.423 3.359a3.36 3.36 0 0 0-3.36-3.36h0a3.36 3.36 0 0 0-3.358 3.36v3.423A3.36 3.36 0 0 0 24 29.07h0a3.36 3.36 0 0 0 3.359-3.36h-3.36");
}

</style>
