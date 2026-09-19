<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v-zwobbwl"/><path class="pto795dxr"/><circle class="whh4kwbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-id" /></template>
<style>
.pto795dxr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.25 24.708V45.08h0a21.6 21.6 0 0 1-4.25.42C12.126 45.5 2.5 35.874 2.5 24c0-7.291 3.63-13.735 9.18-17.623");
}

.v-zwobbwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.75 32.734V2.92A21.6 21.6 0 0 1 24 2.5c11.874 0 21.5 9.626 21.5 21.5c0 7.292-3.63 13.735-9.18 17.623");
}

.whh4kwbeq {
  cx: 28.25px;
  cy: 15.439px;
  r: 0.75px;
  fill: currentColor;
}

</style>
