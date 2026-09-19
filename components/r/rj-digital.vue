<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qjqjqyeie"/><circle class="cpk0fnbgt"/><path class="r2yh4me5i"/><circle class="kppqbwj3u"/><circle class="jcz5wkbkg"/><circle class="d68g-9bwl"/><circle class="goqto9bie"/><path class="tf1cchbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rj-digital" /></template>
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

.d68g-9bwl {
  cx: 42.63px;
  cy: 17.94px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.goqto9bie {
  cx: 7px;
  cy: 32.994px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jcz5wkbkg {
  cx: 18.5px;
  cy: 11.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kppqbwj3u {
  cx: 25.6px;
  cy: 21.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qjqjqyeie {
  cx: 41.25px;
  cy: 33px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r2yh4me5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.262 30.81c-3.689-9.616.955-20.42 10.47-24.36c9.516-3.943 20.44.416 24.63 9.826m1.218 3.774a19 19 0 0 1-.847 10.76m-1.803 3.54a19 19 0 0 1-31.5.55");
}

.tf1cchbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7 31c2.497-10.56 4.73-16.75 9.5-19.5m4 0c2.602 2.5 3.621 3.943 4.191 8.218M9 33h30.25M8.414 31.59c3.254-3.667 9.891-8.05 15.26-9.548M40.63 17.94c-5.199 0-13.08 3.096-13.08 3.096");
}

</style>
