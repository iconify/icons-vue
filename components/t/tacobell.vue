<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-15 24.374 33.5)" class="doxnqgb4s"/><path class="jqcmok9-o"/><ellipse transform="rotate(-15 24.007 32.177)" class="ssqsmzp5q"/><path class="htswmkgti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tacobell" /></template>
<style>
.doxnqgb4s {
  cx: 24.36px;
  cy: 33.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 15.14px;
  ry: 4.13px;
}

.htswmkgti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.87 24.39c-3-1.42-3.81-2-5.59-5.37S29.63 8.93 22.88 8.94a.92.92 0 0 1-.76-.39l-.77-1.16A1.27 1.27 0 0 0 20 6.87l-3.46.93a1.26 1.26 0 0 0-.94 1.26v1.16a.88.88 0 0 1-.46.8c-1.35.73-5.11 3.13-5.81 7.79a69 69 0 0 0-.76 9.09s9.91-6 14.42-3.37");
}

.jqcmok9-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.14 33a5 5 0 0 0 9.11-3.44");
}

.ssqsmzp5q {
  cx: 24px;
  cy: 32.16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.08px;
  ry: 7.63px;
}

</style>
