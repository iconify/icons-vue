<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yrsw-3jpn"/><path class="bhynhic3n"/><path class="uskmjh89s"/><path class="v8k46abtn"/><ellipse class="uk4w7-39t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zencom" /></template>
<style>
.bhynhic3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.593 17.821c-3.173-12.197-19.646-.25-6.973 5.729");
}

.uk4w7-39t {
  cx: 33.205px;
  cy: 6.446px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.266px;
  ry: 2.243px;
}

.uskmjh89s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.622 23.556a13.405 13.405 0 0 1-12.346 13.456c-7.168.733-13.724-3.904-15.062-10.653a13.16 13.16 0 0 1 9.947-15.153");
}

.v8k46abtn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.71 11.31s.813.017.952-1.63c.353-4.486 2-3.448 6.346-3.513c2.656-.374 2.334-3.237-.216-3.48");
}

.yrsw-3jpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.6 17.852A21.499 21.499 0 1 1 26.767 2.68");
}

</style>
