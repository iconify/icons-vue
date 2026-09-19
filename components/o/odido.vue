<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="n3u7j36vn"/><path class="y87hdmqfu"/><circle class="k4g0qzb0w"/><path class="dk5k-ibhv"/><path class="fbn33obsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:odido" /></template>
<style>
.dk5k-ibhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.034 18.017a5.983 5.983 0 1 0 0 11.966z");
}

.fbn33obsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.009 18.017h6.043v11.966h-6.043z");
}

.k4g0qzb0w {
  cx: 39.017px;
  cy: 24px;
  r: 5.983px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n3u7j36vn {
  cx: 8.983px;
  cy: 24px;
  r: 5.983px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y87hdmqfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.966 18.017a5.983 5.983 0 1 1 0 11.966z");
}

</style>
