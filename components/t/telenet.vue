<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="v7e3sjvll"/><path class="tjz7yh5db"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telenet" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.tjz7yh5db {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.274 20.324v-2.75c2.043-.547 4.12-.398 6.183.155v2.73c-2.094-.58-4.095-.694-6.183-.135M33 26.637v1.876c-4.912 4.913-13.093 4.769-18-.138v-1.876s9.537 6.665 18 .138");
}

.v7e3sjvll {
  cx: 19.062px;
  cy: 18.783px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.17px;
  ry: 2.91px;
}

</style>
