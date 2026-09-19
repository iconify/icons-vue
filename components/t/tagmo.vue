<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jh9t8w95t"/><circle class="j_-7wac8d"/><circle class="ll3ccv_lg"/><circle class="gxq6h0bxt"/><circle class="i0iazfb3v"/><circle class="ky523twmo"/><circle class="wcjo-xb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tagmo" /></template>
<style>
.gxq6h0bxt {
  cx: 9.016px;
  cy: 31.518px;
  r: 2.444px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i0iazfb3v {
  cx: 41.128px;
  cy: 23.979px;
  r: 2.372px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j_-7wac8d {
  cx: 6.96px;
  cy: 23.979px;
  r: 2.459px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jh9t8w95t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.97 18.942c.8 1.396 1.303 3.388 1.303 5.595s-.503 4.198-1.304 5.595m3.614-12.72c1.026 1.869 1.642 4.373 1.642 7.125s-.616 5.256-1.642 7.124m-14.156-4.178c-.298-.544-.483-1.653-.483-2.946c0-.914.092-1.725.246-2.32l.004-.002l7.174 5.597h-.002c.41-.801.667-1.972.667-3.275c0-1.704-.43-3.172-1.078-3.891");
}

.ky523twmo {
  cx: 38.678px;
  cy: 16.441px;
  r: 2.403px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ll3ccv_lg {
  cx: 9.016px;
  cy: 16.441px;
  r: 2.345px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wcjo-xb2l {
  cx: 38.678px;
  cy: 31.518px;
  r: 2.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
