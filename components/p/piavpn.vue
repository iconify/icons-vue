<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8g_zg5qw"/><rect class="yzqtfp4pd"/><path class="loj92_7gz"/><path class="o189lcbzb"/><path class="o2dk9pytp"/><path class="pxfu9actt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:piavpn" /></template>
<style>
.loj92_7gz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.352 17.773V15.16a10.66 10.66 0 0 1 21.319 0v2.613");
}

.o189lcbzb {
  fill: currentColor;
  d: path("M21.108 10.984a.75.75 0 1 0-.75.75a.75.75 0 0 0 .75-.75");
}

.o2dk9pytp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.449 14.607a6.1 6.1 0 0 0 2.562.655a6.1 6.1 0 0 0 2.563-.655");
}

.pxfu9actt {
  fill: currentColor;
  d: path("M27.665 10.234a.75.75 0 1 0 .75.75a.75.75 0 0 0-.75-.75");
}

.s8g_zg5qw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.977 25.28a3.261 3.261 0 0 0-1.634 6.074l-1 4.64h5.312l-1-4.64a3.27 3.27 0 0 0 1.61-2.806v-.038a3.266 3.266 0 0 0-3.288-3.23");
}

.yzqtfp4pd {
  width: 31.231px;
  height: 25.727px;
  x: 8.384px;
  y: 17.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
}

</style>
