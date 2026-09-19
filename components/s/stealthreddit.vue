<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vt94z8bsm"/><path class="rn0neiawr"/><path class="m5zw10awr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stealthreddit" /></template>
<style>
.m5zw10awr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.927 29.423l.2 3.45l3.448.2");
}

.rn0neiawr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.82 41.047L42.5 5.5L6.953 20.179l-1.421 1.449l-.032 1.978l10.576-.462l-1.107 1.579l-.043 4.7l-4.516 2.336l-2.69 2.774l7.405-1.661l-1.66 7.407l2.775-2.69l2.334-4.517l4.701-.041l1.579-1.108l-.461 10.577l1.978-.032z");
}

.vt94z8bsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.855 31.923l9.39-18.221l-18.169 9.442");
}

</style>
