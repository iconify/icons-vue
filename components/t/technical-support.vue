<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bn3ekcsej"/><path class="iazhd62-l"/><path class="j4vkz_bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:technical-support" /></template>
<style>
.bn3ekcsej {
  cx: 24px;
  cy: 32.64px;
  r: 2.057px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iazhd62-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.966 16.731c0-1.666.675-3.175 1.767-4.267a6.034 6.034 0 0 1 10.301 4.267c0 1.667-.563 3.3-1.767 4.267c-1.249 1.002-4.289 2.643-4.289 5.196");
}

.j4vkz_bzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.121 21.621C41.121 12.166 33.456 4.5 24 4.5S6.879 12.166 6.879 21.621c0 7.425 4.734 13.728 11.343 16.1L24 43.5l5.778-5.778c6.609-2.373 11.343-8.676 11.343-16.1");
}

</style>
