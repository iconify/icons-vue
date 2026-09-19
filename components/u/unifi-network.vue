<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="onp5v0_ma"/><circle class="g5nbv9bzn"/><path class="ydtsufwbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unifi-network" /></template>
<style>
.g5nbv9bzn {
  cx: 23.992px;
  cy: 24.025px;
  r: 8.746px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.onp5v0_ma {
  cx: 23.924px;
  cy: 24.094px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ydtsufwbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.372 21.933v3.312a1.618 1.618 0 1 0 3.233 0v-3.312");
}

</style>
