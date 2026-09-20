<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ipm9fdcvj"/><rect class="n6zw0vxtb"/><path class="jf9m0abef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:password" /></template>
<style>
.ipm9fdcvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 25.28a3.26 3.26 0 0 0-1.64 6.07V36h3.32v-4.65a3.28 3.28 0 0 0 1.61-2.8A3.27 3.27 0 0 0 24 25.28");
}

.jf9m0abef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.35 17.77v-2.61a10.66 10.66 0 0 1 21.32 0v2.61");
}

.n6zw0vxtb {
  width: 33.23px;
  height: 25.73px;
  x: 7.38px;
  y: 17.77px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.32px;
}

</style>
