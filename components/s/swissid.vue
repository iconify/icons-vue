<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="n4fr9mamk"/><circle class="onvaf8bso"/><circle class="g-yq4glkk"/><circle class="xdpfam7oq"/><circle class="zk64dqbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swissid" /></template>
<style>
.g-yq4glkk {
  cx: 24px;
  cy: 37.806px;
  r: 4.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n4fr9mamk {
  cx: 24px;
  cy: 24px;
  r: 4.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.onvaf8bso {
  cx: 24px;
  cy: 10.194px;
  r: 4.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xdpfam7oq {
  cx: 37.806px;
  cy: 24px;
  r: 4.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zk64dqbjd {
  cx: 10.194px;
  cy: 24px;
  r: 4.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
