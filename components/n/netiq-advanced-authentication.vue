<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kfbarr_0c"/><path class="i5zg880qh"/><circle class="ujy2gzp0e"/><path class="av3vv6bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netiq-advanced-authentication" /></template>
<style>
.av3vv6bpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.123 25.273v-4.082h0h-11.462m8.783 2.354v-2.354");
}

.i5zg880qh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 35.949L29.819 41.46a1.283 1.283 0 0 1-1.795-1.177V14.407a2.57 2.57 0 0 1 1.544-2.354L42.5 6.433Z");
}

.kfbarr_0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 6.433H22.267A2.567 2.567 0 0 0 19.7 8.999v8.342m8.324 18.608h-5.757a2.567 2.567 0 0 1-2.567-2.567v-8.341");
}

.ujy2gzp0e {
  cx: 9.583px;
  cy: 21.191px;
  r: 4.083px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
