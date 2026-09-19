<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0-bh9c7x"/><circle class="s-s-kbkhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naukricom" /></template>
<style>
.s-s-kbkhq {
  cx: 11.657px;
  cy: 8.768px;
  r: 4.268px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x0-bh9c7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.328 4.5c-16.283 9.06-25.671 25.606 3.283 39c-16.545-.92-27.65-11.046-25.869-21.798C16.482 11.197 24.328 6.864 37.328 4.5");
}

</style>
