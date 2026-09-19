<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4p-g0bzm"/><path class="md9jl1bjo"/><circle class="jdisfxbxd"/><circle class="ivoeacboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zxtune" /></template>
<style>
.ivoeacboo {
  cx: 24px;
  cy: 24px;
  r: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jdisfxbxd {
  cx: 24px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k4p-g0bzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.72 40.5H9.28a1.78 1.78 0 0 1-1.78-1.78V9.28A1.78 1.78 0 0 1 9.28 7.5h29.44a1.78 1.78 0 0 1 1.78 1.78v29.44a1.78 1.78 0 0 1-1.78 1.78M9.28 7.5v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m-29.44 39v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3");
}

.md9jl1bjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.72 40.5H9.28a1.78 1.78 0 0 1-1.78-1.78V9.28A1.78 1.78 0 0 1 9.28 7.5h29.44a1.78 1.78 0 0 1 1.78 1.78v29.44a1.78 1.78 0 0 1-1.78 1.78M9.28 7.5v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m-29.44 39v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3M40.5 9.28h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3M4.5 9.28h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3");
}

</style>
