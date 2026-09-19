<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uz924cbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whatsdeleted" /></template>
<style>
.uz924cbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.275 13.707h25.45V39.94a3.56 3.56 0 0 1-3.56 3.56h-18.33a3.56 3.56 0 0 1-3.56-3.56zm19.678-6.138l-.89-3.069H17.937l-.89 3.069H9.328v6.138h29.344V7.569z");
}

</style>
