<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y09skub7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:one-app" /></template>
<style>
.y09skub7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.727 43.5L20.758 37l8.97-6.5l-8.97-6.5l8.97-6.5l-8.97-6.5l8.97-6.5zM20.758 37V11m0 0l-8.485 6.15h8.485");
}

</style>
