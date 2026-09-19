<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kv_39pk3y"/><path class="d0q84pb2t"/><path class="gyhr7hbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoftlens" /></template>
<style>
.d0q84pb2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.43 34a18.5 18.5 0 1 0 0-20m32.46 2.44L24.5 16.4m-2.46-2.47l4.81-8.34m-2.35 26l4.87.01M23.1 42.4l10.67-18.38m6.22 10.83L29.39 16.4");
}

.gyhr7hbsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.75 18.01v11h5.5");
}

.kv_39pk3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16v16a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V16a2 2 0 0 0-2-2h-16a2 2 0 0 0-2 2");
}

</style>
