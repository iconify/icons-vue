<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vvcn42g7e"/><path class="wr39hvbnq"/><path class="tpqdmvz1b"/><path class="v2gmpx4oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uhc" /></template>
<style>
.tpqdmvz1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.353 7.974V31.02a7.238 7.238 0 0 1-14.475 0");
}

.v2gmpx4oh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.238 6.237v25.732a9.18 9.18 0 0 1-18.36 0");
}

.vvcn42g7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.878 14.446L35.122 4.5v27.878c0 6.143-4.98 11.122-11.122 11.122s-11.122-4.98-11.122-11.122z");
}

.wr39hvbnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.469 9.71v21.048a5.295 5.295 0 0 1-10.59 0");
}

</style>
