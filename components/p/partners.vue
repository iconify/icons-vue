<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hibfvpnev"/><path class="iiil1qbzj"/><path class="p4_ydbovk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:partners" /></template>
<style>
.hibfvpnev {
  cx: 17.52px;
  cy: 38.203px;
  r: 5.297px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iiil1qbzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.794 27.42c-.353-3.389 2.944-7.592 7.836-9.599c7.64-3.134 10.148-4.33 10.148-8.267c0-2.82-1.646-5.054-6.465-5.054S12.27 12.257 17.794 27.42");
}

.p4_ydbovk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.662 10.328c1.822-2.116 3.879-3.38 8.052-3.6m-13.85 28.479c-1.49.243-2.733 1.283-2.821 2.919");
}

</style>
