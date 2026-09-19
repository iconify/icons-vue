<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="qtf5yucqi"/><rect class="iodr3eq7e"/><rect class="o025wkhct"/><path class="cuhn1wbea"/><circle class="qdaaic7jc"/><circle class="h-c31tb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixbit" /></template>
<style>
.cuhn1wbea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.386 19.497h9.857v3.734h-6.571v-3.734");
}

.h-c31tb8k {
  cx: 13.542px;
  cy: 16.638px;
  r: 0.75px;
  fill: currentColor;
}

.iodr3eq7e {
  width: 6.067px;
  height: 6.067px;
  x: 34.527px;
  y: 37.409px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.385px;
}

.o025wkhct {
  width: 22.137px;
  height: 6.115px;
  x: 7.355px;
  y: 37.385px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.368px;
}

.qdaaic7jc {
  cx: 34.458px;
  cy: 16.638px;
  r: 0.75px;
  fill: currentColor;
}

.qtf5yucqi {
  width: 33.282px;
  height: 27.12px;
  x: 7.363px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.357px;
}

</style>
