<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gizux1b9s"/><path class="ii8_8-bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wish" /></template>
<style>
.gizux1b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.917 28.754a5.84 5.84 0 0 0 5.909 6.983a8.45 8.45 0 0 0 8.057-6.983");
}

.ii8_8-bgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.883 28.754a5.84 5.84 0 0 0 5.908 6.983a8.45 8.45 0 0 0 8.058-6.983m0 0l.651-9.063m-14.617 9.063l.651-5.868m-14.617 5.868l1.246-11.811L4.5 12.263");
}

</style>
