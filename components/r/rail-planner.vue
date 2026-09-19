<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvkzhr0rg"/><path class="li0nxxb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rail-planner" /></template>
<style>
.li0nxxb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.012 32.728H17.988l3.345-4.247h5.334zm6.689 8.496H11.299l3.345-4.248h18.712z");
}

.wvkzhr0rg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.677 31.401A12.64 12.64 0 0 1 11.3 24c0-7.015 5.686-12.701 12.701-12.701s12.7 5.686 12.7 12.701c0 2.762-.881 5.318-2.379 7.402l5.572 7.077A21.42 21.42 0 0 0 45.5 24c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24a21.42 21.42 0 0 0 5.606 14.48z");
}

</style>
