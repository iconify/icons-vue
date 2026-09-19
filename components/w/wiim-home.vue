<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="yhn02zftr"/><circle class="wo-02tbng"/><path class="s771y08mo"/><circle class="t1qm2xbnf"/><path class="acfhvebxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wiim-home" /></template>
<style>
.acfhvebxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.604 22.855V28.5");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.s771y08mo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.259 22.855V28.5");
}

.t1qm2xbnf {
  cx: 22.604px;
  cy: 20.246px;
  r: 0.75px;
  fill: currentColor;
}

.wo-02tbng {
  cx: 25.259px;
  cy: 20.246px;
  r: 0.75px;
  fill: currentColor;
}

.yhn02zftr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.799 28.49v-8.51l3.43 4.286a1.065 1.065 0 0 0 1.662.001l3.428-4.275V28.5m-16.118-8.511V28.5l-3.43-4.287a1.065 1.065 0 0 0-1.662-.001l-3.428 4.275v-8.508");
}

</style>
