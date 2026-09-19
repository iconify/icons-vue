<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ka3krcy8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:messages-2" /></template>
<style>
.ka3krcy8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 9.3h-33a3 3 0 0 0-3 3v20a3 3 0 0 0 3 3h1.64v7.4l8.26-7.4h23.1a3 3 0 0 0 3-3v-20a3 3 0 0 0-3-3m-29.75 13h26.5m-26.5-6h26.5m-26.5 12h16.5");
}

</style>
