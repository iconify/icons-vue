<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bevgj9b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vatan" /></template>
<style>
.bevgj9b9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.318 17.5l-2.925 9l-2.925-9m14.606 1.125v6.75c0 .675.45 1.125 1.125 1.125h.337m-2.7-6.075h2.475m6.303 3.825a2.257 2.257 0 0 1-2.25 2.25h0a2.257 2.257 0 0 1-2.25-2.25v-1.462a2.257 2.257 0 0 1 2.25-2.25h0a2.257 2.257 0 0 1 2.25 2.25m0 3.712v-6.075m6.918 6.075v-3.712c0-1.238-1.013-2.25-2.25-2.25s-2.25 1.012-2.25 2.25m0 3.712v-6.075M20.573 24.25a2.257 2.257 0 0 1-2.25 2.25h0a2.257 2.257 0 0 1-2.25-2.25v-1.462a2.257 2.257 0 0 1 2.25-2.25h0a2.257 2.257 0 0 1 2.25 2.25m0 3.712v-6.075");
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
