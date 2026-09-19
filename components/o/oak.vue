<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iej9g_g7l"/><path class="e4011fl5m"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oak" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e4011fl5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.213 18.841s4.007.855 6.113 2.256c1.354.9 3.41 2.827 7.314 3.125c2.24.067 3.134-.28 4.02-.754a9.5 9.5 0 0 0 1.724-1.196m-.021.018c.824.687 2.922 2.428 4.449 2.992c2.546.94 6.504-.761 6.799-.944");
}

.iej9g_g7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m2.742 27.236l15.995-15.932L30.363 22.29l5.107-5.078m0 0l3.118 3.618l6.473 7.512");
}

</style>
