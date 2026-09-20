<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="xftxmft_g"/><path class="s1c2ngiks"/><circle class="pfmi-2byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vidhub" /></template>
<style>
.pfmi-2byn {
  cx: 24.485px;
  cy: 9.328px;
  r: 0.75px;
  fill: currentColor;
}

.s1c2ngiks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.387 22.146h23.226c1.108 0 2 .892 2 2v12.519c0 1.108-.892 2-2 2H12.387c-1.108 0-2-.892-2-2V24.146c0-1.108.892-2 2-2M21.295 9.08l-3.137 9.71l-3.136-9.71m9.463 3.155v6.555m8.015-4.127a2.427 2.427 0 0 0-2.413-2.428a2.427 2.427 0 0 0-2.413 2.428v1.578a2.427 2.427 0 0 0 2.413 2.427a2.427 2.427 0 0 0 2.413-2.427m0 2.549V9.08");
}

.xftxmft_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.802 28.605v3.676c0 1.226.996 2.228 2.213 2.228a2.227 2.227 0 0 0 2.214-2.228v-3.676m0 3.788v2.228m-12.537-9.023v9.023m0-3.788c0-1.225.996-2.228 2.214-2.228a2.227 2.227 0 0 1 2.214 2.228v3.676m11.79-3.676c0-1.225.997-2.228 2.214-2.228a2.227 2.227 0 0 1 2.214 2.228v1.448a2.227 2.227 0 0 1-2.214 2.228a2.227 2.227 0 0 1-2.213-2.228m-.001 2.339v-8.91");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
