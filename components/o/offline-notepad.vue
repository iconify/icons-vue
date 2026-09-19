<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="whq9p07wt"/><path class="ith744p8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:offline-notepad" /></template>
<style>
.ith744p8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.016 14.182l-18.798 18.8l-6.704 2.37l2.371-6.704L33.684 9.85");
}

.whq9p07wt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.907 11.268H6.347c-1.02 0-1.847.784-1.847 1.75v28.867c0 .966.827 1.75 1.847 1.75h30.481c1.02 0 1.848-.784 1.848-1.75V19.6m1.927-8.004a3.064 3.064 0 0 0-4.333-4.333l-2.586 2.586l4.332 4.333z");
}

</style>
