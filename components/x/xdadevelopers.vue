<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyudx7l5i"/><rect class="o2aetibdw"/><rect class="mie24ph_r"/><path class="ejj8g8b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xdadevelopers" /></template>
<style>
.ejj8g8b5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 21.559v9.834m-21.607-9.834L9.5 31.393m7.393 0L9.5 21.559M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.mie24ph_r {
  width: 7.393px;
  height: 9.834px;
  x: 31.107px;
  y: 21.559px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.696px;
  ry: 3.696px;
}

.o2aetibdw {
  width: 7.393px;
  height: 9.834px;
  x: 20.148px;
  y: 21.559px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.696px;
  ry: 3.696px;
}

.yyudx7l5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.541 16.607v14.786");
}

</style>
