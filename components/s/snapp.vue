<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="lt67sibvn"/><path class="xh6aspbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snapp" /></template>
<style>
.lt67sibvn {
  cx: 20.419px;
  cy: 38.403px;
  r: 5.097px;
}

.xh6aspbnw {
  d: path("M32.678 4.5L28.04 22.089c-1.111 4.217-1.8 7.656-6.212 7.698l-4.314.041L24.3 4.508z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
