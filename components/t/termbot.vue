<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjh9_tb6x"/><circle class="x1eswvbfu"/><path class="nw_lv81-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:termbot" /></template>
<style>
.mjh9_tb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 8.4a4 4 0 0 0-4 4v23.2a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4V12.4a4 4 0 0 0-4-4zM9 23.13v.03l7.72 6L9 35.13m20.46 0h-11");
}

.nw_lv81-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.706 23.078l-5.183-5.184a4.264 4.264 0 0 0-7.063-4.368a4.268 4.268 0 0 0 4.998 6.8l.784.783l.481-.48l3.49 3.49l2.258.12z");
}

.x1eswvbfu {
  cx: 28.674px;
  cy: 15.739px;
  r: 1.385px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
