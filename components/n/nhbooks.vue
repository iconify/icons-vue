<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qbhtstlzo"/><path class="q6o4o_4ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nhbooks" /></template>
<style>
.q6o4o_4ra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 37.461V17.838l13 19.623V17.838");
}

.qbhtstlzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 8.5v31a4 4 0 0 0 4 4h23.2a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4h-.921v9.821l-3.887-3.91l-3.884 3.91V4.5H12.4a4 4 0 0 0-4 4");
}

</style>
