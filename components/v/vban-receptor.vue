<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="brxpxfbzn"/><path class="a7y8ympkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vban-receptor" /></template>
<style>
.a7y8ympkn {
  d: path("M5.5 18.101h37M9.251 38.95h1.967m-1.967-1.967h1.967m-1.967-1.967h1.967m1.966 0h1.967m-1.967 1.967h1.967m-1.967 1.967h1.967m-1.967-5.9h1.967m-1.967-1.967h1.967m1.966 0h1.967m-1.967 1.967h1.967m-1.967 1.966h1.967m-1.967 1.967h1.967m-1.967 1.967h1.967m1.966 0h1.967m-1.967-1.967h1.967m-1.967-1.967h1.967M21.05 33.05h1.967m-1.967-1.967h1.967m-1.967-1.966h1.967m1.966 0h1.967m-1.967-1.967h1.967m-1.967-1.966h1.967m1.966 0h1.967m-1.967-1.967h1.967m1.966 1.967h1.967m1.966 5.899h1.967m-1.967 1.967h1.967m-1.967 1.966h1.967m-1.967 1.967h1.967m-1.967 1.967h1.967m-5.9 0h1.967m-1.967-1.967h1.967m-1.967-1.967h1.967m-1.967-1.966h1.967m-1.967-1.967h1.967m-1.967-1.966h1.967m-1.967-1.967h1.967m-5.9 0h1.967m-1.967 1.967h1.967m-1.967 1.966h1.967m-1.967 1.967h1.967m-1.967 1.966h1.967m-1.967 1.967h1.967m-1.967 1.967h1.967m-5.9 0h1.967m-1.967-1.967h1.967m-1.967-1.967h1.967m-1.967-1.966h1.967m-1.967-1.967h1.967");
}

.brxpxfbzn {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
