<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmi5d587k"/><path class="u66nyfbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:povo2-supporter" /></template>
<style>
.bmi5d587k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.25h39v19.5h-39zm0 7.8l7.8-7.8m23.4 19.5l7.8-7.8");
}

.u66nyfbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.789 24c1.613 0 2.92 1.326 2.92 2.963s-1.307 2.962-2.92 2.962h-4.818v-11.85h4.818c1.613 0 2.92 1.326 2.92 2.962S33.402 24 31.79 24zm0 0h-4.812m-5.948-2c0-2.168-1.732-3.926-3.87-3.926S13.292 19.832 13.292 22v4c0 2.168 1.732 3.925 3.869 3.925S21.03 28.168 21.03 26h-3.87");
}

</style>
