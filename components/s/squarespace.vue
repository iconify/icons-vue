<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x88q16b4j"/><path class="rnlxpipfq"/><path class="chq4h0blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:squarespace" /></template>
<style>
.chq4h0blj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.512 15.805L15.805 27.512a6.622 6.622 0 1 1-9.365-9.365l9.365-9.366");
}

.rnlxpipfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.488 32.195l11.707-11.707a6.622 6.622 0 1 1 9.365 9.365l-9.365 9.366m-21.073-16.39L22.83 11.122a6.62 6.62 0 0 1 9.365 0");
}

.x88q16b4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.878 25.171L25.17 36.878a6.62 6.62 0 0 1-9.365 0");
}

</style>
