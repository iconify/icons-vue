<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sfmnlbcdj"/><path class="huxpqhujo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noble-fokus" /></template>
<style>
.huxpqhujo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 24L24 8.008L14.75 24");
}

.sfmnlbcdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 40.215V7.785l-16.965 29.74c-.678 1.188-2.392 1.188-3.07 0L5.5 7.785v32.43z");
}

</style>
