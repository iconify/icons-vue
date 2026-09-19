<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z452y_bat"/><circle class="hj7umc59y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vietnamnet" /></template>
<style>
.hj7umc59y {
  cx: 20.047px;
  cy: 15.358px;
  r: 2.659px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z452y_bat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 18.903c3.454 1.994 9.9 10.464 11.966 18.17L43.5 10.927L16.466 29.54V18.903z");
}

</style>
