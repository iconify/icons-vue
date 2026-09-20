<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m82vhpb4n"/><path class="ori9o9idz"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mifareclassictool" /></template>
<style>
.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.m82vhpb4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.38 18.62a2.48 2.48 0 0 1 2.46 2.47m-2.46-4.37a4.27 4.27 0 0 1 4.29 4.25V21");
}

.ori9o9idz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.38 14.89A6.12 6.12 0 0 1 39.5 21m-31 8.51v-8.58l4.29 8.58l4.3-8.58v8.58m10.01-8.58h5.72m-2.86 8.58v-8.58m-4.61 5.72za2.85 2.85 0 0 1-2.84 2.86h-.02a2.85 2.85 0 0 1-2.86-2.84v-2.88a2.85 2.85 0 0 1 2.84-2.86h.02a2.85 2.85 0 0 1 2.86 2.84v.02");
}

</style>
