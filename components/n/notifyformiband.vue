<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="sl2khybij"/><circle class="h-yq491hm"/><path class="me2ijzwvg"/><path class="gi-s6_qrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notifyformiband" /></template>
<style>
.gi-s6_qrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.15 13.05l-3.14 3.13l-6.67-6.67m0 0L8.46 12.4");
}

.h-yq491hm {
  cx: 13.3px;
  cy: 34.83px;
  r: 5.81px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.me2ijzwvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.24 11.39a2.16 2.16 0 1 1 0-3.05a2.13 2.13 0 0 1 .63 1.49a2.18 2.18 0 0 1-.63 1.56m7.6-1.52a.9.9 0 0 0-.91.9V21.2a.9.9 0 0 0 .9.91H43a.9.9 0 0 0 .91-.9V10.77a.9.9 0 0 0-.9-.9zm15.29 1.76l-7.22 5.31l-7.22-5.31M4.89 22.7l9.82-9.82m-4.07 4.06L14 20.39l-3.67 3.68");
}

.sl2khybij {
  width: 33.06px;
  height: 11.63px;
  x: 7.47px;
  y: 29.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.81px;
}

</style>
