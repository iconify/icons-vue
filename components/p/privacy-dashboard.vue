<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvw5eo13b"/><circle class="otp9zxbyl"/><path class="vofjl2xbi"/><rect class="vsw1fik4u"/><path class="k23g-ebqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacy-dashboard" /></template>
<style>
.bvw5eo13b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.753 18.688a4.634 4.634 0 0 1 9.269 0m0 0v2.789m-9.269-2.789v2.752");
}

.k23g-ebqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.447 34.748A21.499 21.499 0 1 1 23.828 2.5");
}

.otp9zxbyl {
  cx: 22.387px;
  cy: 27.343px;
  r: 1.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vofjl2xbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.387 30.534v-1.528");
}

.vsw1fik4u {
  width: 12.848px;
  height: 12.848px;
  x: 15.963px;
  y: 21.098px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.545px;
}

</style>
