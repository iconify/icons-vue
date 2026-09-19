<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lfoz0uobk"/><path class="tnhz5ct0x"/><path class="qid__5x5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:portaphone" /></template>
<style>
.lfoz0uobk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 43.5v-35c0-2.216-1.784-4-4-4h-23c-2.216 0-4 1.784-4 4v35");
}

.qid__5x5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28L8.5 43.5h31z");
}

.tnhz5ct0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 38.5v-29h21v29");
}

</style>
