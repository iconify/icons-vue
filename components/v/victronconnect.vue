<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yfvx3y_xc"/><path class="lx7on7w_j"/><circle class="wl2xvxb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:victronconnect" /></template>
<style>
.lx7on7w_j {
  fill: none;
  stroke: currentColor;
  d: path("m15.153 11.836l19.614 25.739M14.765 27.319l7.24-5.809");
}

.wl2xvxb6c {
  cx: 12.871px;
  cy: 28.686px;
  r: 2.288px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yfvx3y_xc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.8 28.414A11.65 11.65 0 1 1 13.107 17.17m7.155 1.211a11.65 11.65 0 1 1 15.553 12.157");
}

</style>
