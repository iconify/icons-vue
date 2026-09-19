<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zaej40lzx"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sms-gate" /></template>
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

.zaej40lzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.646 28.525a3.48 3.48 0 0 0 2.92 1.314h1.75a2.93 2.93 0 0 0 2.92-2.92h0A2.93 2.93 0 0 0 12.316 24H10.42a2.93 2.93 0 0 1-2.92-2.92h0a2.93 2.93 0 0 1 2.92-2.919h1.751a3.13 3.13 0 0 1 2.919 1.314m3.022 10.364V18.16l5.838 11.68l5.838-11.678V29.84m3.122-1.315a3.48 3.48 0 0 0 2.92 1.314h1.75a2.93 2.93 0 0 0 2.92-2.92h0A2.93 2.93 0 0 0 37.58 24h-1.897a2.93 2.93 0 0 1-2.92-2.92h0a2.93 2.93 0 0 1 2.92-2.919h1.752a3.13 3.13 0 0 1 2.919 1.314");
}

</style>
