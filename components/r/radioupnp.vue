<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ggj6x-0qx"/><path class="qt6ozsbjl"/><path class="bam67ec1r"/><path class="mbx3vgifb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:radioupnp" /></template>
<style>
.bam67ec1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.874 15.225a4.808 4.808 0 0 1 8.328 0m-7.732 5.981a3.606 3.606 0 0 1 3.606-3.607h0a3.606 3.606 0 0 1 3.606 3.606h0m.001 10.577a3.606 3.606 0 1 1-7.213 0m7.213-10.576v10.576M20.47 21.206v10.576");
}

.ggj6x-0qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.59 9.51a12.02 12.02 0 0 1 20.82 0");
}

.mbx3vgifb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.25 32.201a7.213 7.213 0 0 1-14.424 0m7.328 7.212v5.068m-3.296.019h6.399m3.993-15.402v3.103m-14.424-3.103v3.103");
}

.qt6ozsbjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.745 12.107a8.415 8.415 0 0 1 14.575 0");
}

</style>
