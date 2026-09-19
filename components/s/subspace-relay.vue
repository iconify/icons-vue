<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1fo7nbtr"/><circle class="sed03ninj"/><path class="idkmuibrb"/><path class="ohzh5lb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subspace-relay" /></template>
<style>
.e1fo7nbtr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.714 32.29c5.2 3.5 7.1 6 6.5 7c-.7 1.3-8-1.5-16.2-6.2s-14.2-9.6-13.5-10.9c.6-1 4.4-.7 10 2");
}

.idkmuibrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.714 16.79c1.7.3 3.3 1.1 4.6 2.4c2.1 2.1 2.8 4.9 2.4 7.6m-7-14.2c2.8.3 5.5 1.5 7.6 3.6c2.9 2.9 4.1 6.8 3.6 10.6");
}

.ohzh5lb-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.714 8.39c4.1.1 8 1.7 11.1 4.7c3.7 3.7 5.2 8.7 4.6 13.8m-12.3 6.4c3.8 2.8 5.6 5.1 5.1 6c-.7 1.3-8-1.5-16.2-6.2s-14.2-9.6-13.5-10.9c.4-.8 3.2-.7 7.1.8");
}

.sed03ninj {
  cx: 21.214px;
  cy: 29.691px;
  r: 7.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
