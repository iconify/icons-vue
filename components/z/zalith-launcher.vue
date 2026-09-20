<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5y5o0gcr"/><path class="bkamjrbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zalith-launcher" /></template>
<style>
.bkamjrbkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.74 8.962l21.772-2.125l.379 15.925l-6.66.36l-.056 3.252l-6.429.471l-.018 6.374l13.357-.351l.148 6.974l-23.288.213l.564-15.953l6.207-.351l.13-3.122l6.327-.416l-.009-6.19l-12.304.795z");
}

.s5y5o0gcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.698 6.985L36.101 4.5l1.69 7.445l.287 16.877l-5.543.24l-.018 1.801l4.046-.101l1.829 3.649l.138 8.877l-22.964.212l-6.096-1.727l.693-19.63l5.874-.508l-5.736-5.81z");
}

</style>
