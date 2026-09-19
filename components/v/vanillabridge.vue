<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ldy3edbcm"/><circle class="xhg7k7bzv"/><circle class="o7xry4b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vanillabridge" /></template>
<style>
.ldy3edbcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.089 43.5c7.299-11.67 8.261-17.605 8.261-22.939c0-2.658-.12-7.62-2.647-7.62c-2.486 0-3.609 5.467-3.609 9.906c0 12.632 5.857 19.931 8.785 19.931c4.97 0 9.032-16.883 9.032-22.217c0-2.658-.12-7.62-2.647-7.62c-2.486 0-3.609 5.467-3.609 9.906c0 5.29 1.188 9.926 2.654 13.201");
}

.o7xry4b_h {
  cx: 30.985px;
  cy: 7.067px;
  r: 2.567px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xhg7k7bzv {
  cx: 19.342px;
  cy: 7.067px;
  r: 2.567px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
