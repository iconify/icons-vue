<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mw3sdvbku"/><path class="h50q0lbto"/><path class="mx6-j-bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mileage" /></template>
<style>
.h50q0lbto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.19 4.5h8.3v16.1");
}

.mw3sdvbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.59 13.9v29.6h18.9v-23H8.59m-2.4 23h23.6M8.59 10.2V4.5h7.3");
}

.mx6-j-bzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.49 20.5c.5-.9 1.4-2 2.6-2c1.4 0 2.9.7 2.9 3.6c0 1.1 0 8.5.3 9.9s1.1 3.9 4.2 3.9c3.3 0 4.5-4.1 4.3-6.1a105 105 0 0 0-1.9-10.9c-.7-3.4-3.6-6.9-3.9-8.7a9.47 9.47 0 0 0-3-4.6a9 9 0 0 0-1.8-1");
}

</style>
