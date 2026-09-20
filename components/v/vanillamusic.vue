<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhd33obud"/><circle class="bd51oabjp"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vanillamusic" /></template>
<style>
.bd51oabjp {
  cx: 24px;
  cy: 24px;
  r: 5.144px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qhd33obud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.108 8.5a1.58 1.58 0 0 1 1.59 1.57v.038a1.58 1.58 0 0 1-1.57 1.589h-.02a1.58 1.58 0 0 1-1.607-1.55v-.039A1.58 1.58 0 0 1 10.108 8.5m27.784 0a1.58 1.58 0 0 1 1.608 1.608a1.58 1.58 0 0 1-1.57 1.59h-.019a1.58 1.58 0 0 1-1.608-1.55v-.04a1.58 1.58 0 0 1 1.55-1.608zM24 9.47c8.025 0 14.531 6.506 14.531 14.531S32.025 38.531 24 38.531S9.469 32.025 9.469 24S15.975 9.469 24 9.469M10.108 36.303c.878 0 1.59.711 1.59 1.589a1.58 1.58 0 0 1-1.55 1.608h-.04A1.58 1.58 0 0 1 8.5 37.892a1.58 1.58 0 0 1 1.608-1.59Zm27.784 0a1.58 1.58 0 0 1 1.607 1.55v.039a1.58 1.58 0 0 1-1.607 1.608a1.58 1.58 0 0 1-1.59-1.57v-.019a1.58 1.58 0 0 1 1.57-1.589h.02z");
}

</style>
