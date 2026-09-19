<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ry_n8abko"/><rect class="exc5pcmls"/><path class="kcvmqvbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simpill" /></template>
<style>
.exc5pcmls {
  width: 16.059px;
  height: 8.029px;
  x: 15.971px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.kcvmqvbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.985 14.823v-2.294m8.03 2.294v-2.294m-10.324 8.603h12.618v16.059H17.691zm2.868 8.03h6.882m-6.882 3.441h6.882m-6.882-6.882h2.294m2.294 0h2.294");
}

.ry_n8abko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.25 14.824h11.5a4 4 0 0 1 4 4V41.5a2 2 0 0 1-2 2h-15.5a2 2 0 0 1-2-2V18.824a4 4 0 0 1 4-4");
}

</style>
