<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ayzgtlsnc"/><path class="ip55w0wlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mijn-eetmeter" /></template>
<style>
.ayzgtlsnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.742 16.046a2.094 2.094 0 0 1 2.097 2.091v.002c0 .685-.334 1.288-.843 1.67a.83.83 0 0 0-.415.718v10.59a.84.84 0 0 1-.839.837");
}

.ip55w0wlw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.097 16.046h21.806A2.094 2.094 0 0 1 37 18.137v.002c0 .685-.334 1.288-.843 1.67a.83.83 0 0 0-.415.718v10.59a.84.84 0 0 1-.839.837H13.097a.84.84 0 0 1-.84-.837v-10.59a.83.83 0 0 0-.414-.719A2.08 2.08 0 0 1 11 18.14c0-1.156.938-2.093 2.095-2.093z");
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

</style>
