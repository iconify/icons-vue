<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ccegb62zo"/><path class="nw5rnabgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rimi" /></template>
<style>
.ccegb62zo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.318 7.77c6.53-3.577 12.916-2.85 14.427 1.641c2.688 7.985-4.71 25.292-16.155 33.089c6.256-12.095 6.256-19.439 6.256-24.536s-1.332-7.17-4.528-10.194");
}

.nw5rnabgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.075 10.71c5.81-3.182 10.693-1.642 12.037 2.353c2.392 7.104-9.983 21.92-23.903 25.588");
}

</style>
