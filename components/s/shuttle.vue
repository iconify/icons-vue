<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="goqpjnb9z"/><circle class="x5mcb3b7e"/><path class="lrm-1twhi"/><path class="yw9obt1ht"/><circle class="xclcw8pct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shuttle" /></template>
<style>
.goqpjnb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.794 15.379v18.305");
}

.lrm-1twhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.675 8.169H42.5v9.482H30.131l-.511-2.272");
}

.x5mcb3b7e {
  cx: 11.647px;
  cy: 33.684px;
  r: 6.147px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xclcw8pct {
  cx: 36.353px;
  cy: 35.956px;
  r: 6.147px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yw9obt1ht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.298 15.379H17.794V5.897h12.369zM42.5 17.651v18.305");
}

</style>
