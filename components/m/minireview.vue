<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mm05ab33z"/><circle class="erx3y81co"/><circle class="ug9-ybchj"/><circle class="xuy2_370t"/><path class="ezkz8nkhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minireview" /></template>
<style>
.erx3y81co {
  cx: 15.608px;
  cy: 16.58px;
  r: 3.553px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ezkz8nkhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 27.679l1.514 3.068l3.387.492l-2.451 2.389l.579 3.373L24 35.408l-3.029 1.593l.579-3.373l-2.451-2.389l3.387-.492zm10.979 5.976l1.182 2.396l2.644.384l-1.913 1.865l.451 2.633l-2.364-1.243l-2.365 1.243l.452-2.633l-1.914-1.865l2.644-.384zm-21.958 0l1.183 2.396l2.644.384l-1.914 1.865l.452 2.633l-2.365-1.243l-2.364 1.243l.451-2.633l-1.913-1.865l2.644-.384z");
}

.mm05ab33z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.015 23.606c7.065.072 8.62 10.644 16.174 7.604c6.367-2.563 1.899-14.056.18-17.828c-2.073-4.551-5.423-6.123-8.083-6.15c-3.18-.033-5.347 2.73-8.132 2.702S19.258 7.1 16.08 7.067c-2.66-.027-6.041 1.476-8.207 5.985C6.077 16.788 1.377 28.19 7.69 30.88c7.49 3.193 9.259-7.346 16.324-7.274");
}

.ug9-ybchj {
  cx: 31.005px;
  cy: 14.7px;
  r: 1.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xuy2_370t {
  cx: 34.911px;
  cy: 18.686px;
  r: 1.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
