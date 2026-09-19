<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ye0ye-6ag"/><path class="n-mm3qbkp"/><path class="r2fn6bb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nevertoomanybooks" /></template>
<style>
.n-mm3qbkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.552 34.382l-4.755-.034l-1.297 3.89l36.961.109l-1.783-3.891l-12.05-.039");
}

.r2fn6bb-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.065 38.303l-.053-24.976h3.121");
}

.ye0ye-6ag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.211 31.157l.853 1.807l1.73.084l-1.282 1.442l.46 1.857l-1.761-.87l-1.532.866l.256-1.853l-1.487-1.442l1.872-.084zm-2.443-13.07v10.998h4.664V18.087zM5.5 38.239v1.783h37l-.054-1.675M11.552 34.15h5.636M11.66 11.868l5.528.053M11.66 38.257V7.978h5.528v30.294m7.829-22.027h-7.829m10.999 22.058l-.054-24.976");
}

</style>
