<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="qlvzi6_6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rg-digital-sp" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.qlvzi6_6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 30.692V17.308h4.382c2.477 0 4.485 2.012 4.485 4.495s-2.008 4.495-4.485 4.495H13.5m4.382 0l4.381 4.391M34.5 21.742a4.433 4.433 0 0 0-4.433-4.434h0a4.433 4.433 0 0 0-4.434 4.434v4.517a4.433 4.433 0 0 0 4.434 4.433h0a4.433 4.433 0 0 0 4.433-4.433h-4.433");
}

</style>
