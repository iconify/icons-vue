<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><path class="y23qrj0fy"/><path class="fnv6gvbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-3" /></template>
<style>
.fnv6gvbiy {
  d: path("M19.2 17.336c1.107-.922 2.3-1.343 4.979-1.336l.622.004a4 4 0 1 1 0 7.998m-3.074 0h3.074");
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

.y23qrj0fy {
  d: path("M19.202 30.65c1.104.926 2.297 1.35 4.975 1.35h.624a4 4 0 1 0 0-7.998");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
