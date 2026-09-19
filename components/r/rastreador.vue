<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kdxk90b1c"/><circle class="yl7l7dbcw"/><path class="l4q1frb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rastreador" /></template>
<style>
.kdxk90b1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.883 31.633a13.41 13.41 0 0 1-17.362-1.364c-5.235-5.236-5.235-13.724 0-18.96s13.724-5.236 18.96 0a13.41 13.41 0 0 1 1.365 17.362l1.495 1.495a15.5 15.5 0 0 0-1.378-20.338c-6.054-6.054-15.87-6.054-21.923 0c-6.054 6.054-6.054 15.87 0 21.923L24 42.712l9.48-9.48z");
}

.l4q1frb3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.071 27.86l3.891 3.89");
}

.yl7l7dbcw {
  cx: 23.999px;
  cy: 20.788px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
