<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mns89ywps"/><path class="ing_nnbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-vodafone" /></template>
<style>
.ing_nnbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.79 13.41a3.3 3.3 0 0 1 .31-1.21c1.09-2.54 4.9-6.29 7.77-7.29v-.08c-13.47 0-20.6 8.35-20.6 19.17a10.75 10.75 0 1 0 12.52-10.59");
}

.mns89ywps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 1 2.5 24A21.51 21.51 0 0 1 24 2.5");
}

</style>
