<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5vq5dy4r"/><circle class="qr1l1c7tm"/><path class="h11wzgbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yahoo" /></template>
<style>
.h11wzgbqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.465 23.96h-7.96L34.57 6.987h7.93z");
}

.p5vq5dy4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.27h7.299l4.25 10.874l4.305-10.873h7.107L17.76 41.01h-7.152l2.93-6.82z");
}

.qr1l1c7tm {
  cx: 29.591px;
  cy: 30.005px;
  r: 4.421px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
