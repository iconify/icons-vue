<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ircy-ibfy"/><path class="u539pxbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netbird" /></template>
<style>
.ircy-ibfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.153 37.77h15.93L42.5 10.43s-7.968-.024-11.82 0s-5.46 2.787-6.784 4.762S11.153 37.77 11.153 37.77");
}

.u539pxbop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.083 37.77L5.5 14.72s11.717-2.053 18.278.785s8.649 12.783 8.649 12.783z");
}

</style>
