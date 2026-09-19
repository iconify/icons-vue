<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s830p4myd"/><path class="mkswmrkeh"/><rect class="siqckjb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oeffiplans" /></template>
<style>
.mkswmrkeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.37 32.67v2.93l-5.03 5.02");
}

.s830p4myd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.51 21.51 0 0 0 24 2.5M6.93 21.27h12.64m7.59 0h13.91M6.93 26.43h12.64m7.59 0h13.91m-17.7-11.46V7.38");
}

.siqckjb6g {
  width: 7.59px;
  height: 17.71px;
  x: 19.57px;
  y: 14.97px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
