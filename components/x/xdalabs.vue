<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w22o8accz"/><rect class="tcbnaccla"/><rect class="dvm11ivlb"/><path class="ju6z7c_xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xdalabs" /></template>
<style>
.dvm11ivlb {
  width: 5.05px;
  height: 6.72px;
  x: 28.85px;
  y: 28.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.52px;
}

.ju6z7c_xu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.9 28.21v6.72m-14.75-6.72l-5.05 6.72m5.05 0l-5.05-6.72m27.28-8.37h-7.86l-7.77-13a2 2 0 0 0-3.5 0l-7.77 13H6.62a3.12 3.12 0 0 0-3 3.93L8 40.08a2.84 2.84 0 0 0 2.74 2.1h26.5a2.84 2.84 0 0 0 2.76-2.1l4.41-16.31a3.12 3.12 0 0 0-3.03-3.93m-17.38-8l4.77 8h-9.54Zm-9.52 8h19.04");
}

.tcbnaccla {
  width: 5.05px;
  height: 6.72px;
  x: 21.37px;
  y: 28.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.52px;
}

.w22o8accz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.42 24.83v10.1");
}

</style>
