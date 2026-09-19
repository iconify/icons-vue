<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wefbopjdk"/><circle class="z_bn-6bko"/><path class="gfemqbbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vix" /></template>
<style>
.gfemqbbvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.389 22.062v8.603m-4.286-12.986l-4.301 12.986L10.5 17.679");
}

.wefbopjdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-9.603 12.179L37.5 30.665m0-12.986l-8.603 12.986");
}

.z_bn-6bko {
  cx: 23.389px;
  cy: 18.085px;
  r: 0.75px;
  fill: currentColor;
}

</style>
