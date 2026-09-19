<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xonx9sy-j"/><circle class="fturw2a6a"/><circle class="va5lok6xx"/><circle class="x8zz9w6uw"/><circle class="sdqby7e8u"/><path class="wpzfacbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miner-gun-builder" /></template>
<style>
.fturw2a6a {
  cx: 38.5px;
  cy: 37.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sdqby7e8u {
  cx: 37.5px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.va5lok6xx {
  cx: 24px;
  cy: 22px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wpzfacbzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.632 10.302l-4.765 9.896m1.111 2.095l9.543 1.414m2.127 2.287l.704 9.511");
}

.x8zz9w6uw {
  cx: 30.5px;
  cy: 8.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xonx9sy-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 5.5h10v10h-10zm0 13.5h10v10h-10zm0 13.5h10v10h-10zm13.5 0h10v10H21z");
}

</style>
