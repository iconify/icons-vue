<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mrkozmbgb"/><path class="tnmhncc6u"/><path class="xx_mnobwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-hq" /></template>
<style>
.mrkozmbgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.283 39.418a6.283 6.283 0 0 0-12.566 0H7.67V18.067L24 5.5l16.329 12.567v21.351z");
}

.tnmhncc6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.183 28.112c8.794-8.795 18.84-8.795 27.634 0");
}

.xx_mnobwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.955 33.135c6.273-6.283 13.817-6.283 20.09 0M24 36.337c1.7 0 3.082 1.38 3.082 3.081S25.7 42.5 24 42.5s-3.082-1.38-3.082-3.082S22.3 36.337 24 36.337");
}

</style>
