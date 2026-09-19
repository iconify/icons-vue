<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oujs_6dal"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vw-banking" /></template>
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

.oujs_6dal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.643 27.61v-7.22H32.2M28.643 24h2.313m2.967 2.816c.435.578.983.793 1.746.793h1.055c.982 0 1.776-.808 1.776-1.802v-.008A1.79 1.79 0 0 0 36.724 24H35.56a1.79 1.79 0 0 1-1.777-1.803h0c0-.998.794-1.803 1.78-1.803h1.047c.764 0 1.312.212 1.746.79m-15.08-.793l-1.78 7.218l-1.78-7.218l-1.776 7.218l-1.784-7.218m-1.943 0l-2.358 7.218L9.5 20.391");
}

</style>
