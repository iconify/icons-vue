<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vqogbbbht"/><path class="k2lqj8byo"/><path class="c2xrbabwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tempusromanum" /></template>
<style>
.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.k2lqj8byo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.363 31V17h4.55c2.625 0 4.725 2.1 4.725 4.725s-2.1 4.725-4.725 4.725h-4.55m4.9 0L36.638 31M12.363 17h9.275m-4.55 0v14");
}

.vqogbbbht {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
