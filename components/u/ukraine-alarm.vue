<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gemx54bbp"/><path class="bh-_jcb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ukraine-alarm" /></template>
<style>
.bh-_jcb_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.051 27.876c7.697 0 12.533 3.364 17.748 8.075V12.05c-5.215 4.71-10.051 8.075-17.748 8.075M33.8 27.028a3.028 3.028 0 1 0 0-6.056m-22.627 6.904v13.379");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gemx54bbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.173 20.124h4.878v7.752h-4.878z");
}

</style>
