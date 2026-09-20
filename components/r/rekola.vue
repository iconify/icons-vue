<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tfpvx5qje"/><path class="tj21hybsz"/><path class="lbhig4but"/><path class="v86l77brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rekola" /></template>
<style>
.lbhig4but {
  fill: none;
  stroke: currentColor;
  d: path("M15.602 21.745a7.297 7.297 0 1 1-3.805-1.07m4.472-1.639l11.521-.073");
}

.tfpvx5qje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.504 16.25l-3.201 11.947H36.26m-10.957-.001L14.594 17.53l-2.798 10.444l4.056-15.134s-3.482-.678-4.16-.096c-.947.812-.765 2.646 1.483 2.404");
}

.tj21hybsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.362 26.62c1.618-6.031 7.712-6.328 10.857-4.488a7.42 7.42 0 0 1 2.765 8.89a7.296 7.296 0 0 1-13.706-.7");
}

.v86l77brn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.79 15.716l4.162-.058");
}

</style>
