<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yh9ve7avf"/><rect class="wv_zsqg8y"/><path class="x8ci11bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notecryptpro" /></template>
<style>
.wv_zsqg8y {
  width: 17.96px;
  height: 12.57px;
  x: 15.02px;
  y: 27.28px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.09px;
}

.x8ci11bds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.11a1.42 1.42 0 0 1 1.42 1.43a1.39 1.39 0 0 1-.55 1.12l.67 2.34h-3.08l.67-2.35a1.39 1.39 0 0 1-.55-1.12A1.42 1.42 0 0 1 24 31.11m-5.94-3.83v-2.49a5.94 5.94 0 1 1 11.88 0v2.49");
}

.yh9ve7avf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2Zm-11-11l11 11");
}

</style>
