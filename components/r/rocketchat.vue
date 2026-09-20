<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o37310bjt"/><path class="iljcmcbvb"/><circle class="mkifztyzd"/><circle class="vni3b8bjj"/><circle class="qkc06cb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rocketchat" /></template>
<style>
.iljcmcbvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.69 16.39C12.17 13 18 10.83 24.76 10.9");
}

.mkifztyzd {
  cx: 16.7px;
  cy: 24.5px;
  r: 2.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o37310bjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24.1a10.5 10.5 0 0 0-1.7-5.6a13 13 0 0 0-4.3-4.1a24.17 24.17 0 0 0-13.1-3.5a25 25 0 0 0-4.8.4a20 20 0 0 0-3.3-2.4a13.42 13.42 0 0 0-11.8-.1s5 4.1 4.2 7.6A10.84 10.84 0 0 0 5.3 24a10.67 10.67 0 0 0 3.4 7.6c.8 3.6-4.2 7.6-4.2 7.6a13.23 13.23 0 0 0 11.7-.1a15.5 15.5 0 0 0 3.3-2.4a26 26 0 0 0 4.8.4a24.17 24.17 0 0 0 13.1-3.5a15.4 15.4 0 0 0 4.3-4.1a8.57 8.57 0 0 0 1.8-5.4");
}

.qkc06cb2t {
  cx: 31.9px;
  cy: 24.5px;
  r: 2.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vni3b8bjj {
  cx: 24.3px;
  cy: 24.5px;
  r: 2.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
