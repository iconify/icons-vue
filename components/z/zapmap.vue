<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="urp09cban"/><path class="fs8rrqmfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zapmap" /></template>
<style>
.fs8rrqmfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.302 39.487L31 23.5H17L30.015 5.714");
}

.urp09cban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.11 7.303a15.5 15.5 0 0 1 23.862 16.71C36.096 34.744 24 43.5 24 43.5S11.904 34.744 9.028 24.012a15.5 15.5 0 0 1 6.081-16.709z");
}

</style>
