<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o4ai9hbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vk-teams" /></template>
<style>
.o4ai9hbpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 5.5a6 6 0 0 0-4.242 1.758l-5 5a6 6 0 0 0 0 8.484a6 6 0 0 0 8.484 0l5-5a6 6 0 0 0 0-8.484A6 6 0 0 0 36.5 5.5m-25.001 0a6 6 0 0 1 4.242 1.758l5 5a6 6 0 0 1 0 8.484a6 6 0 0 1-8.484 0l-5-5a6 6 0 0 1 0-8.484A6 6 0 0 1 11.499 5.5m25.002 37a6 6 0 0 1-4.242-1.758l-5-5a6 6 0 0 1 0-8.484a6 6 0 0 1 8.484 0l5 5a6 6 0 0 1 0 8.484a6 6 0 0 1-4.242 1.758m-25.001 0a6 6 0 0 0 4.242-1.758l5-5a6 6 0 0 0 0-8.484a6 6 0 0 0-8.484 0l-5 5a6 6 0 0 0 0 8.484A6 6 0 0 0 11.5 42.5");
}

</style>
