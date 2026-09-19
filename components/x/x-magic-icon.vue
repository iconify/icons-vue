<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wuh7gut7a"/><path class="abs7ic90l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:x-magic-icon" /></template>
<style>
.abs7ic90l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.176 15.493l8.494-7.092l6.83 6.83l-8.145 11.175");
}

.wuh7gut7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.371 26.92c0-7.002-5.676-12.679-12.679-12.679s-12.679 5.677-12.679 12.68c0 5.533-5.513 8.107-5.513 8.107s6.137 4.571 18.192 4.571c7.003 0 12.68-5.676 12.68-12.679");
}

</style>
