<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nsc5_ybxi"/><path class="kq6yz8b2a"/><circle class="lzyv8l4fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ventra" /></template>
<style>
.kq6yz8b2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.585 4.5L24 24.486L32.415 4.5");
}

.lzyv8l4fc {
  cx: 24px;
  cy: 40.002px;
  r: 3.498px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nsc5_ybxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.585 13.318L24 33.305l8.415-19.987");
}

</style>
