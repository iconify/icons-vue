<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z6w830bwc"/><path class="q3tahobqo"/><path class="zf4xg2zfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quran" /></template>
<style>
.q3tahobqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.32 26.39a2 2 0 0 1-2-2v6h-6a2 2 0 1 1-2 2a2 2 0 0 1 2-2h-6v-6a2 2 0 1 1-2-2a2 2 0 0 1 2 2v-6h6a2 2 0 1 1 2-2a2 2 0 0 1-2 2h6v6a2 2 0 1 1 2 2M8.4 6.45v35.1a2 2 0 0 0 1.95 2h2.38V4.5h-2.38A2 2 0 0 0 8.4 6.45");
}

.z6w830bwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.32 22.39h4v4h-4z");
}

.zf4xg2zfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.73 4.5v39h24.92a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95Z");
}

</style>
