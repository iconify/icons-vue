<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kpz7jsxyb"/><path class="dptw-pblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mark" /></template>
<style>
.dptw-pblp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 43h23a4 4 0 0 0 4-4V8a4 4 0 0 0-4-4h-23a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4");
}

.kpz7jsxyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.243 18.006l.01-2.514l2.504.01m13 2.504l-.01-2.514l-2.504.01m-13 13.492l.01 2.514l2.504-.01m13-2.505l-.01 2.515l-2.504-.01M24.016 21.5l-.032 4M26 23.516l-4-.032");
}

</style>
