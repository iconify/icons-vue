<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><rect class="r68jh1bff"/><path class="ekrcp48kv"/><circle class="mcf5p9x-i"/><path class="cpw9anbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:osu" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpw9anbbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.03 15.49v9.43");
}

.ekrcp48kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.57 20v5.23a3.16 3.16 0 0 0 3.17 3.17h0a3.16 3.16 0 0 0 3.16-3.17V20m0 5.19v3.17m-15.04-.71a3.56 3.56 0 0 0 2.61.71h.71a2.1 2.1 0 0 0 2.1-2.1h0a2.1 2.1 0 0 0-2.1-2.1h-1.42a2.1 2.1 0 0 1-2.1-2.1h0a2.1 2.1 0 0 1 2.1-2.1h.71a3.56 3.56 0 0 1 2.61.71");
}

.mcf5p9x-i {
  cx: 38.03px;
  cy: 28.17px;
  r: 0.75px;
  fill: currentColor;
}

.r68jh1bff {
  width: 6.34px;
  height: 8.4px;
  x: 9.22px;
  y: 19.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.17px;
}

</style>
