<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jcd_lpbsa"/><path class="rfsi60bpi"/><path class="r84cohbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transmission-btc" /></template>
<style>
.jcd_lpbsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.236 36.12h25.52l-2.127-16.157h-7.236l1.28 10.2h3.83l-8.931 5.101l-8.507-5.1h3.83l1.703-10.201h-7.236z");
}

.r84cohbxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.445 12.304l-8.813-.028c-3.406 0-3.406-5.532 0-5.532l8.813.036m5.525 5.524l8.389-.028c3.406 0 3.406-5.532 0-5.532l-8.813.036M19.49 28.506h9.01");
}

.rfsi60bpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.236 16.557h10.21V5.5h5.1v11.057h10.21L41.008 42.5H6.99z");
}

</style>
