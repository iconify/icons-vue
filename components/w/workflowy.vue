<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dzaxw8ivp"/><path class="igzq4gbzr"/><circle class="f00ulw57u"/><path class="s7na7gsrq"/><circle class="wv81e_kut"/><path class="gc6eanb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:workflowy" /></template>
<style>
.dzaxw8ivp {
  cx: 10.693px;
  cy: 11.106px;
  r: 5.194px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f00ulw57u {
  cx: 11.127px;
  cy: 36.894px;
  r: 5.194px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gc6eanb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.61 21.28h15.562c3.025 0 3.037 6.092 0 6.092h-15.56");
}

.igzq4gbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.241 8.507h24.37c3.032 0 3.386 5.745.334 5.745H14.972");
}

.s7na7gsrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.675 34.294h24.37c3.031 0 3.385 5.745.333 5.745H15.405");
}

.wv81e_kut {
  cx: 20.355px;
  cy: 24.306px;
  r: 4.985px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
