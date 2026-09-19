<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qv33t297i"/><path class="kwtoowblb"/><path class="z6xuryb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-planner" /></template>
<style>
.kwtoowblb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.8h12.3v16.7c0 1.1-.9 2-2 2H7.5c-1.1 0-2-.9-2-2v-33c0-1.1.9-2 2-2h22.9");
}

.qv33t297i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.2 29.5h10.3c1.1 0 2-.9 2-2v-20c0-1.1-.9-2-2-2H30.2V34c0 1.1-.9 2-2 2H17.8");
}

.z6xuryb4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.8 5.5v13.2h12.35");
}

</style>
