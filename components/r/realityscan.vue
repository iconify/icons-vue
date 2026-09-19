<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s351oouyx"/><path class="k1qpuofjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:realityscan" /></template>
<style>
.k1qpuofjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.9 31.102h8.2L32.2 24l-4.1-7.102h-8.2L15.8 24zm19.56 5.472L32.2 24M8.54 11.426L15.8 24M27.16 4.324L19.9 16.898m.94 26.778l7.26-12.574m-22.72 0H19.9m22.72-14.204H28.1");
}

.s351oouyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.62 33.595v-19.19a2 2 0 0 0-1-1.732L25 3.077a2 2 0 0 0-2 0L6.38 12.673a2 2 0 0 0-1 1.732v19.19a2 2 0 0 0 1 1.732L23 44.923a2 2 0 0 0 2 0l16.62-9.596a2 2 0 0 0 1-1.732");
}

</style>
