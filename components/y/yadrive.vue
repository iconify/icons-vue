<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o3q_tv0jt"/><rect class="hew4piqcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yadrive" /></template>
<style>
.hew4piqcg {
  width: 36.991px;
  height: 36.991px;
  x: 5.505px;
  y: 5.504px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.999px;
  ry: 3.999px;
}

.o3q_tv0jt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.689 8.3c.894-.097 2.09-.232 2.911-.265c5.096-.199 8.816.813 11.384 2.722c3.424 2.545 4.596 6.623 4.235 10.926c-.638 7.617-5.781 16.263-12.094 20.817m12.157 0c7.897-6.846 12.328-14.003 13.387-20.53c1.008-6.223-1.06-11.902-5.648-16.47");
}

</style>
