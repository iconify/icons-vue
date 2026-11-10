<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zczaeh_oj"/><path class="b3ddoojdr"/><path class="hrrb5bbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thaimart" /></template>
<style>
.b3ddoojdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.827 37.127c2.29-.854 4.5-2.712 4.5-5.96v-11.12c0-5.948 8.61-13.487 17.077-7.435c5.267 3.764 6.53 11.605-.417 13.9");
}

.hrrb5bbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.724 24.393a1.513 1.513 0 0 1-3.026 0a1.513 1.513 0 0 1 3.026 0");
}

.zczaeh_oj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.212 37.619h3.896a4.73 4.73 0 0 1 4.72-4.741h.366a4.73 4.73 0 0 1 4.742 4.718v.024H39.61c9.553-12.696-2.079-25.187-11.69-23.97");
}

</style>
