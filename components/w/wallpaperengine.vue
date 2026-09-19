<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s510v1bfb"/><path class="mbh5w5bid"/><path class="gt62fubvd"/><path class="d8g4x_cvh"/><path class="wz6misyeu"/><path class="eg4hdccpy"/><circle class="fr0jjbcqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallpaperengine" /></template>
<style>
.d8g4x_cvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.606 34.571h13.53a4.356 4.356 0 0 0 4.364-4.367V9.862a4.354 4.354 0 0 0-4.364-4.365H17.794a4.357 4.357 0 0 0-4.368 4.365");
}

.eg4hdccpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.502 29.903l-2.862 2.862l2.62 2.595l2.862-2.862");
}

.fr0jjbcqa {
  cx: 24px;
  cy: 24px;
  r: 4.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gt62fubvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.499 18.097l2.861-2.862l-2.62-2.594l-2.862 2.861m-5.272 19.07a11.18 11.18 0 0 1-9.49-17.086");
}

.mbh5w5bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.006 13.429v-3.235h4.262v3.61m3.611 1.698l2.861-2.862l2.595 2.62l-2.862 2.862m2.1 7.847h3.235v-4.262h-3.61");
}

.s510v1bfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.396 13.428a11.18 11.18 0 0 1 9.489 17.086m-9.49-17.085H9.865A4.356 4.356 0 0 0 5.5 17.796v20.342a4.354 4.354 0 0 0 4.365 4.365h20.341a4.357 4.357 0 0 0 4.368-4.365");
}

.wz6misyeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.995 34.571v3.235h-4.263v-3.61m-3.609-1.698L15.26 35.36l-2.595-2.621l2.862-2.862m-2.098-7.846h-3.236v4.262h3.61");
}

</style>
