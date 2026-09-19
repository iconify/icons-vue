<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lidcuzbzp"/><circle class="wz6zfip8d"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wiz" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lidcuzbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 20.653l2.342 7.986a.85.85 0 0 0 1.616.047l1.893-5.289a.829.829 0 0 1 1.579.058l1.434 5.174a.83.83 0 0 0 1.58.058l3.565-9.937m2.038 10.487v-4.414m2.241-4.073h6.799a1.264 1.264 0 0 1 .676 2.33l-6.037 3.825a1.264 1.264 0 0 0 .677 2.332H38.5");
}

.wz6zfip8d {
  cx: 25.547px;
  cy: 22.562px;
  r: 0.75px;
  fill: currentColor;
}

</style>
