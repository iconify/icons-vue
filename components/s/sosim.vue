<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="db8hsgb3x"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sosim" /></template>
<style>
.db8hsgb3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.803 20.284v7.432m2.265-.008v-7.424l3.716 7.432l3.716-7.421v7.421m-16.738-.814c.456.593 1.028.814 1.823.814h1.1c1.024 0 1.854-.83 1.854-1.854v-.008c0-1.024-.83-1.854-1.854-1.854h-1.214a1.856 1.856 0 0 1-1.856-1.856a1.86 1.86 0 0 1 1.86-1.86h1.095c.795 0 1.366.221 1.822.814M9.647 26.902c.456.593 1.027.814 1.822.814h1.1c1.025 0 1.855-.83 1.855-1.854v-.008c0-1.024-.83-1.854-1.854-1.854h-1.214A1.856 1.856 0 0 1 9.5 22.144a1.86 1.86 0 0 1 1.86-1.86h1.094c.795 0 1.367.221 1.823.814m2.059 3.552a1.858 1.858 0 1 1 3.716 0v1.208a1.858 1.858 0 1 1-3.716 0z");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
