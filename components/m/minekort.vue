<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i-tisycor"/><path class="ezxh7wbar"/><path class="o2j3v9bgl"/><path class="o5-eyvo9w"/><path class="ba2omabrr"/><path class="m3ihcsbae"/><path class="v5pxucr0a"/><path class="i_zoi6b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minekort" /></template>
<style>
.ba2omabrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.76 18.044a6.53 6.53 0 0 1 13.058 0");
}

.ezxh7wbar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.409 29.91v-9.023a2.76 2.76 0 0 0-2.76-2.76H8.546a2.76 2.76 0 0 0-2.76 2.76v9.023");
}

.i_zoi6b0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.262 36.245l-.987-1.709h-1.974l-.987 1.709m-2.657-4.602l2.657 4.602m3.645-6.312l-2.658 4.603m1.974 0h5.316");
}

.i-tisycor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.432 24.367h2.861v2.778h-2.861zm-.008 9.613h2.861v2.778h-2.861zm.032-18.645h2.861v2.778h-2.861z");
}

.m3ihcsbae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.262 18.044l-.987-1.709h-1.974l-.987 1.709m-2.657-4.602l2.657 4.602m3.645-6.312l-2.658 4.602m1.974 0h5.316M20.76 27.145a6.53 6.53 0 0 1 13.058 0");
}

.o2j3v9bgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.409 37.02v-7.11a2.76 2.76 0 0 0-2.76-2.76H8.546a2.76 2.76 0 0 0-2.76 2.76v7.11m35.623-16.133v-9.22a2.76 2.76 0 0 0-2.76-2.76H8.546a2.76 2.76 0 0 0-2.76 2.76v9.22");
}

.o5-eyvo9w {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 2 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 39.094h39");
}

.v5pxucr0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.262 27.145l-.987-1.71h-1.974l-.987 1.71m-2.657-4.603l2.657 4.603m3.645-6.312l-2.658 4.602m1.974 0h5.316M20.76 36.245a6.53 6.53 0 0 1 13.058 0");
}

</style>
