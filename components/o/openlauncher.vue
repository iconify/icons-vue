<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="p4od-tbho"/><path class="f8rzhmbeo"/><path class="ujfkhtbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openlauncher" /></template>
<style>
.f8rzhmbeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4h0a4 4 0 0 1-4 4h-25");
}

.p4od-tbho {
  width: 37px;
  height: 8px;
  x: 5.5px;
  y: 34.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
}

.ujfkhtbqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.5v-29a4 4 0 0 1 4-4h0a4 4 0 0 1 4 4v25");
}

</style>
