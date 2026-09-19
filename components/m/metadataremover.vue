<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="uhx3m_1tm"/><rect class="d59msu0zs"/><path class="qdui-obhg"/><circle class="wqsgbtebx"/><circle class="flmk1ds9n"/><circle class="c-r9igbqy"/><circle class="cxt1gebhb"/><circle class="gy4y0kyzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metadataremover" /></template>
<style>
.c-r9igbqy {
  cx: 11.9px;
  cy: 30.505px;
  r: 0.75px;
  fill: currentColor;
}

.cxt1gebhb {
  cx: 11.9px;
  cy: 34.64px;
  r: 0.75px;
  fill: currentColor;
}

.d59msu0zs {
  width: 31px;
  height: 21px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.flmk1ds9n {
  cx: 19.75px;
  cy: 12.815px;
  r: 2.921px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gy4y0kyzy {
  cx: 11.9px;
  cy: 38.5px;
  r: 0.75px;
  fill: currentColor;
}

.qdui-obhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.15 7.21c-.554 0-1 .447-1 1v13.72l2.93-2.719l3.26 3.21L27 13.51l9.55 9.144a1 1 0 0 0 .3-.714V8.21a1 1 0 0 0-1-1zm2.68 23.3h6.43m0 4.13h-6.43m0 3.86h6.51m7.11-6.91l5.73 5.73m-5.75.04l5.73-5.73");
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.wqsgbtebx {
  cx: 31.325px;
  cy: 34.465px;
  r: 6.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
