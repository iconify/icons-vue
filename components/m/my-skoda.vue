<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ovg8q0byj"/><path class="ljpmdvg6w"/><circle class="yl2w-6bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-skoda" /></template>
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

.ljpmdvg6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.185 8.35c3.086 1.66 6.338 5.865 6.338 5.865m-13.773 0a20.3 20.3 0 0 1 6.848 3.56");
}

.ovg8q0byj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.71 30.87c.841.924 3.112 3.952 3.533 5.382h2.691l2.23-1.43h16.584v1.683s4.822-1.01 5.79-2.818c-1.178-2.06-3.873-3-5.383-3.238v1.906h-2.482s2.075-2.972 2.075-9.813s-2.916-11.551-7.178-15.7c-9.42.448-16.426 3.64-18.729 14.971c7.626.897 11.874 6.252 11.089 10.738a10.8 10.8 0 0 0-4.08-1.745Z");
}

.yl2w-6bys {
  cx: 27.028px;
  cy: 28.093px;
  r: 2.047px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
