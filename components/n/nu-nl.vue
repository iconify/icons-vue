<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bd99ylv2t"/><circle class="afr13ow1v"/><path class="vfwbcs2jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nu-nl" /></template>
<style>
.afr13ow1v {
  cx: 38.75px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bd99ylv2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.58 30.39C35 37.18 28.44 42 20.75 42c-9.94 0-18-8.06-18-18s8.06-18 18-18C28.44 6 35 10.82 37.58 17.61");
}

.vfwbcs2jn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.855 17.386v12.696a1 1 0 0 1-1 1h-7.13a1 1 0 0 1-1-1V17.386M7.855 31.082V18.386a1 1 0 0 1 1-1h7.13a1 1 0 0 1 1 1V31.08m23.781-10.715v5.63c0 .444.36.804.804.804h.241m-2.905.001v-2.655a1.609 1.609 0 1 0-3.217 0m0 2.654v-4.263");
}

</style>
