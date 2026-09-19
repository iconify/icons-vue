<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="overie6wb"/><path class="gb2ep6b1j"/><path class="ytbup0bdq"/><circle class="gw4_xccmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:momo" /></template>
<style>
.gb2ep6b1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.357V9.466c0-1.985 1.851-3.964 3.965-3.964c2.119 0 3.965 1.978 3.965 3.964v11.891");
}

.gw4_xccmj {
  cx: 34.571px;
  cy: 34.571px;
  r: 7.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.overie6wb {
  cx: 34.571px;
  cy: 13.429px;
  r: 7.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytbup0bdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.429 9.465c0-1.985 1.85-3.964 3.964-3.964c2.119 0 3.965 1.978 3.965 3.964v11.891M5.5 42.5V30.608c0-1.985 1.85-3.965 3.964-3.965c2.119 0 3.965 1.979 3.965 3.965V42.5m0-11.892c0-1.985 1.85-3.965 3.964-3.965c2.119 0 3.965 1.979 3.965 3.965V42.5");
}

</style>
