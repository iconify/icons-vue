<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="uht7ywbce"/><circle class="f7f2h1b2c"/><path class="zvhigvbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tubi" /></template>
<style>
.f7f2h1b2c {
  cx: 35.447px;
  cy: 16.699px;
  r: 0.75px;
  fill: currentColor;
}

.uht7ywbce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.365 20.384v4.962a3.007 3.007 0 1 0 6.015 0v-4.962");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.zvhigvbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.447 20.384v7.969M11.5 17.902v7.444a3.007 3.007 0 0 0 3.008 3.007h.407M11.5 20.384h3.039m11.801 3.007a3.007 3.007 0 1 1 6.015 0v1.955a3.007 3.007 0 1 1-6.015 0m.001 0v-9.023");
}

</style>
