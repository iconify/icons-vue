<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lyjerxb5t"/><path class="tnglfgpxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telegraph" /></template>
<style>
.lyjerxb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24A21.5 21.5 0 1 1 24 45.5");
}

.tnglfgpxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.73 23.465l18-8.014a1.174 1.174 0 0 1 1.638 1.243l-2.417 16.39a1.173 1.173 0 0 1-1.994.655l-2.982-3.007a21.1 21.1 0 0 0-10.102-5.674l-2.04-.486a.587.587 0 0 1-.104-1.107");
}

</style>
