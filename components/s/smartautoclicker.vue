<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l9d_1jb2r"/><path class="g077g133q"/><path class="bb4nswbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartautoclicker" /></template>
<style>
.bb4nswbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.093 26.877a5.183 5.183 0 1 1 7.52-2.887");
}

.g077g133q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.89 22.865l4.82 12.995l-4.42.584a2 2 0 0 0-1.164.653c-.328.359-1.038 1.127-.597 1.329l8.689 3.972l9.286-3.262a1.34 1.34 0 0 0 .613-1.454l-1.434-7.232a1.4 1.4 0 0 0-1.005-1.134l-7.747-.844l-.796.464l-2.678-7.238a2.115 2.115 0 0 0-2.408-1.082a2 2 0 0 0-1.159 2.249");
}

.l9d_1jb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.707 33.206h-9.643a1.356 1.356 0 0 1-1.206-1.205V6.808a1.356 1.356 0 0 1 1.206-1.205h15.188a1.356 1.356 0 0 1 1.205 1.205v22.023");
}

</style>
