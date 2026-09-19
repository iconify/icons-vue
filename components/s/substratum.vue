<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p2sxgzdvr"/><path class="d55fyh34y"/><path class="dlquaacui"/><path class="ebht9rb3m"/><circle class="w-1qeybjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:substratum" /></template>
<style>
.d55fyh34y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.55 7.15A2.64 2.64 0 0 1 23.5 7l8.63 5a2.66 2.66 0 0 1 1.3 2.61");
}

.dlquaacui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.74 21.68l11.73-6.77a2.65 2.65 0 0 1 3.61 1l5 8.63a2.65 2.65 0 0 1-.18 2.91");
}

.ebht9rb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.74 27.26h19.12a2.64 2.64 0 0 1 2.64 2.64v10a2.64 2.64 0 0 1-2.64 2.64H13.12");
}

.p2sxgzdvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.14 5.5h10a2.64 2.64 0 0 1 2.64 2.64v26.74a7.62 7.62 0 0 1-7.62 7.62h0a7.62 7.62 0 0 1-7.66-7.62V8.14A2.64 2.64 0 0 1 8.14 5.5");
}

.w-1qeybjh {
  cx: 13.12px;
  cy: 34.88px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
