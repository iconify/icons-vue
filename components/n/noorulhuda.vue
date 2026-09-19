<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="thhgibh2p"/><path class="fj87w8b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noorulhuda" /></template>
<style>
.fj87w8b-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 35h9V13h-9m9 0h8m-8 22h8m9-22h-9v22h9");
}

.thhgibh2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c-4.17-4.036-11-2.763-11-7.15v-24.7c0-4.387 6.83-3.114 11-7.15c4.17 4.036 11 2.763 11 7.15v24.7c0 4.387-6.83 3.114-11 7.15");
}

</style>
