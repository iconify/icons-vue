<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f4cwobb6e"/><circle class="ypi354_ok"/><circle class="ga4bzcf5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-optimum" /></template>
<style>
.f4cwobb6e {
  cx: 17.639px;
  cy: 24px;
  r: 4.38px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ga4bzcf5q {
  cx: 37.478px;
  cy: 31.117px;
  r: 6.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ypi354_ok {
  cx: 17.639px;
  cy: 24px;
  r: 13.139px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
