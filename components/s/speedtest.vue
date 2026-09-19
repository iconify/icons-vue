<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="edgifbb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:speedtest" /></template>
<style>
.edgifbb2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.29 2a22 22 0 0 1 15.27 37.57l-4.11-4.11a16.2 16.2 0 1 0-22.86-.05l-4.15 4.16A22 22 0 0 1 24.29 2m8.52 13.21L26.94 27h-5.88v-5.91Z");
}

</style>
