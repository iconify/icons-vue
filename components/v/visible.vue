<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xeod87w2w"/><circle class="cgif9hhvs"/><circle class="rsirktblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:visible" /></template>
<style>
.cgif9hhvs {
  cx: 15.429px;
  cy: 21.75px;
  r: 0.75px;
  fill: currentColor;
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

.rsirktblt {
  cx: 23.771px;
  cy: 21.75px;
  r: 0.75px;
  fill: currentColor;
}

.xeod87w2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.03 22.75l-2 5.3l-2-5.3m8.925 4.853c.365.307.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325s-.592-1.325-1.322-1.325h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447m4.926 1.453a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0m0 2v-8m5.75 0v7a1 1 0 0 0 1 1h.3m5.488-1.009a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4");
}

</style>
