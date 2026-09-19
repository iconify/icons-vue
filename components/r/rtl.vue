<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aful-72my"/><path class="oo9mxyb_g"/><path class="mofi1idfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rtl" /></template>
<style>
.aful-72my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 19.5h13.667v9H3.5zm13.667 0h13.667v9H17.167z");
}

.mofi1idfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.667 21.832v4h6M7.333 26v-4h4.66c.74 0 1.34.601 1.34 1.343s-.6 1.344-1.34 1.344h-4.66m4.66 0l1.309 1.312M21 22h6m-3 4v-4");
}

.oo9mxyb_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.833 19.5H44.5v9H30.833z");
}

</style>
