<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpvq6zt1l"/><circle class="xv9xeibjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nrk" /></template>
<style>
.tpvq6zt1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 17.202h4.932v13.595H4.5zm14.195 0h4.932v13.595h-4.932zm10.01 0h4.932v13.595h-4.932zm14.795 0h-4.932L33.637 24l4.931 6.798H43.5L38.568 24zM18.695 30.798h-4.931L9.432 17.202h2.171c1.644 0 3.1 1.064 3.598 2.63z");
}

.xv9xeibjl {
  cx: 26.093px;
  cy: 19.668px;
  r: 2.466px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
