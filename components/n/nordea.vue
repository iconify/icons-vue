<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="meufweb1n"/><rect class="f12g2-7my"/><path class="k5ygl2bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nordea" /></template>
<style>
.f12g2-7my {
  width: 3.908px;
  height: 5.178px;
  x: 15.576px;
  y: 22.73px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.954px;
  ry: 1.954px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.k5ygl2bbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.24 24.684c0-1.08.875-1.954 1.954-1.954h0m-1.954 0v5.178m18.26-1.954c0 1.08-.875 1.954-1.954 1.954h0a1.954 1.954 0 0 1-1.954-1.954v-1.27c0-1.08.875-1.954 1.954-1.954h0c1.08 0 1.954.875 1.954 1.954m0 3.224v-3.224m-5.942 2.238c-.337.59-.971.986-1.698.986h0a1.954 1.954 0 0 1-1.955-1.954v-1.27c0-1.08.875-1.954 1.955-1.954h0c1.079 0 1.954.875 1.954 1.954v.635h-3.909m-1.71-.635c0-1.08-.875-1.954-1.954-1.954h0a1.954 1.954 0 0 0-1.954 1.954v1.27c0 1.08.875 1.954 1.954 1.954h0c1.08 0 1.954-.875 1.954-1.954m0 1.954v-7.816");
}

.meufweb1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 27.908v-7.816l5.178 7.816v-7.816");
}

</style>
