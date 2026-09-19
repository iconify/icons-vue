<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bj-kj6bja"/><rect class="jwj2babvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:recon" /></template>
<style>
.bj-kj6bja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 5.5h-21a8 8 0 0 0-8 8v21a8 8 0 0 0 8 8h21a8 8 0 0 0 8-8v-21a8 8 0 0 0-8-8");
}

.jwj2babvj {
  width: 15px;
  height: 15px;
  x: 16.5px;
  y: 16.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
