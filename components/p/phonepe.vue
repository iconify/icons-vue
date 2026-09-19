<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="k_yg6pbmj"/><path class="dlohc2bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phonepe" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dlohc2bbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.97 18.831c0 3.128-.119 7.93-.119 9.02a4.233 4.233 0 0 0 4.964 4.297a30 30 0 0 0 5.191-1.117");
}

.k_yg6pbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.805 8.5l9.092 10.331m-15.66 0h21.526M29.287 39.5c-.443-9.006-.39-20.669-.39-20.669");
}

</style>
