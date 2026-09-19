<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o1b4lsbuf"/><path class="h7pf2db9l"/><circle class="jpf4-acat"/><circle class="qoo-yn7my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meetme" /></template>
<style>
.h7pf2db9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.098 29.843c9.802 5.6 18.048 4.784 25.827-4.843");
}

.jpf4-acat {
  cx: 16.882px;
  cy: 19.944px;
  r: 2.528px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o1b4lsbuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5C12.126 3.5 2.5 13.126 2.5 25c0 4.2 1.223 8.107 3.306 11.418l-1.663 8.36l9.142-1.157A21.4 21.4 0 0 0 24 46.5c11.874 0 21.5-9.626 21.5-21.5S35.874 3.5 24 3.5");
}

.qoo-yn7my {
  cx: 28.356px;
  cy: 17.726px;
  r: 2.528px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
