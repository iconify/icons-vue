<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzq_7zbob"/><rect class="j3s9ivbxi"/><path class="d7dshub9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:termux-widget" /></template>
<style>
.d7dshub9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.203 16.046h4.655c.355 0 .642.33.642.736v4.468c0 .406-.287.735-.642.735h-4.655c-.355 0-.642-.329-.642-.735v-4.468c0-.407.287-.736.642-.736M26.76 8.5h4.655c.355 0 .642.33.642.736v4.468c0 .406-.287.735-.642.735H26.76c-.355 0-.642-.329-.642-.735V9.236c0-.407.287-.736.642-.736m-.003 7.48h4.656c.354 0 .642.33.642.736v4.468c0 .406-.288.736-.642.736h-4.656c-.354 0-.642-.33-.642-.736v-4.468c0-.406.288-.736.642-.736");
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

.mzq_7zbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.5 25.327l10.127 5.853L10.5 37.032m22 0H21.673");
}

</style>
