<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rbix2yijr"/><circle class="e7yw9-blw"/><path class="frr7tebpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vpnhotspot" /></template>
<style>
.e7yw9-blw {
  cx: 19.21px;
  cy: 24.22px;
  r: 3.95px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.frr7tebpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.42 27.21a8.75 8.75 0 1 1 0-6h16.73v6H41v6.9h-6.11v-6.9Z");
}

.rbix2yijr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.94 27.21a14.07 14.07 0 0 1-6.49 9.06m-14.45 0a14.06 14.06 0 1 1 20.75-15.81c.07.25.14.51.19.77");
}

</style>
