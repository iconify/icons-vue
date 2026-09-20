<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rjcxlf4vk"/><circle class="y7wjnqbhe"/><circle class="br26ht2gs"/><circle class="y0w_7-6kn"/><circle class="ewp2hibdj"/><path class="wbzao6i0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:squid" /></template>
<style>
.br26ht2gs {
  cx: 30.124px;
  cy: 24.569px;
  r: 2.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ewp2hibdj {
  cx: 17.876px;
  cy: 24.569px;
  r: 0.75px;
  fill: currentColor;
}

.rjcxlf4vk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.167 42.941V25.926M22.611 44.5V27.103m-2.778 13.791V25.926m5.556 14.968V27.103");
}

.wbzao6i0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.25 22.256a24.9 24.9 0 0 0 2.01-9.797v-.699A8.26 8.26 0 0 0 24 3.5m-4.213 22.38a4.06 4.06 0 0 0 2.903 1.223h2.62a4.06 4.06 0 0 0 2.903-1.223M24 3.5za8.26 8.26 0 0 0-8.26 8.26v.699a24.9 24.9 0 0 0 2.01 9.797");
}

.y0w_7-6kn {
  cx: 30.124px;
  cy: 24.569px;
  r: 0.75px;
  fill: currentColor;
}

.y7wjnqbhe {
  cx: 17.876px;
  cy: 24.569px;
  r: 2.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
