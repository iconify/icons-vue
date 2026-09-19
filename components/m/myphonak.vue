<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q7sb41maf"/><path class="cul1yccio"/><path class="ny_pzwbrq"/><rect class="xpmxudbvd"/><path class="ifuf63ydn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myphonak" /></template>
<style>
.cul1yccio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 5.504c-3.795 5.266-5.407 10.091-5.345 14.579c.066 4.724 1.988 9.074 5.174 13.17M19.5 5.504c5.579 6.806 8.887 17.587-.171 27.749");
}

.ifuf63ydn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.743 36.275h2.875");
}

.ny_pzwbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.812 18.437c7.627 4.203 15.482 3.215 19.09 2.701");
}

.q7sb41maf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.402 32.42a13.877 13.877 0 1 1 7.83-18.905");
}

.xpmxudbvd {
  width: 13.877px;
  height: 24.978px;
  x: 28.347px;
  y: 17.522px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.974px;
}

</style>
