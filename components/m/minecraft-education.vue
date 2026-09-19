<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b4j956b4m"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minecraft-education" /></template>
<style>
.b4j956b4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.401 9.75H9.75v4.75M24 38.25h9.561m-14.16 0H24v-19m9.561-4.75V9.75H24v9.5h-4.599V14.5M24 9.75h-4.599m0 4.75H9.75v4.75h9.651V24M9.75 24v14.25h9.651V24L9.75 19.25zM33.561 9.75h4.689v4.75h-4.689v23.75h4.689V14.5");
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
