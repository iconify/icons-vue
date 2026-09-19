<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnh26obkq"/><path class="d8lhd0b9y"/><circle class="anun-ju1s"/><path class="jgnn2fbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:now-playing-history" /></template>
<style>
.anun-ju1s {
  cx: 25.197px;
  cy: 27.991px;
  r: 3.944px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cnh26obkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.618 35.518A16.27 16.27 0 0 0 27.18 40.32c9.013 0 16.32-7.307 16.32-16.32S36.193 7.68 27.18 7.68S10.86 14.987 10.86 24");
}

.d8lhd0b9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.799 31.051l6.3-7.051H4.5z");
}

.jgnn2fbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.14 27.991V16.642m0 0h5.038v3.184H29.14z");
}

</style>
