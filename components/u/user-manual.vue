<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o707_xbjc"/><ellipse class="ddtuthbsi"/><path class="mj8t2sbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:user-manual" /></template>
<style>
.ddtuthbsi {
  cx: 25.531px;
  cy: 33.668px;
  fill: currentColor;
  rx: 0.823px;
  ry: 0.75px;
}

.mj8t2sbyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.301 20.049a6.43 6.43 0 0 1 1.959-4.763a7.27 7.27 0 0 1 5.224-1.786c3.918 0 7.183 2.977 7.183 6.549a6.43 6.43 0 0 1-1.959 4.762c-1.632 1.19-5.224 2.977-5.224 5.656");
}

.o707_xbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.33-2v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
