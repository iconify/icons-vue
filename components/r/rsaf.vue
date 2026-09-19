<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="so4vxrbde"/><path class="v7oo4-rcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rsaf" /></template>
<style>
.so4vxrbde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.57 11.971a4 4 0 0 1 4-4h5.823c.699 0 1.38.219 1.95.625l4.118 2.942c.57.407 1.25.625 1.95.625H38.5a4 4 0 0 1 4 4v13.796a4 4 0 0 1-4 4H15.57a4 4 0 0 1-4-4z");
}

.v7oo4-rcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.002 40.029H9.5a4 4 0 0 1-4-4v-19.56m26.412 10.598h-8.913c-4.838 0-4.029-7.28.823-5.666c0-4.043 7.28-4.043 7.28.81c4.047-.81 4.047 4.856.81 4.856");
}

</style>
