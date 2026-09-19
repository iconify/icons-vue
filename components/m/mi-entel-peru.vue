<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yodp4f73w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-entel-peru" /></template>
<style>
.yodp4f73w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.985 23.497H4.5c0-20.416 23.485-20.416 23.485 0m0 12.252C17.771 43.925 4.5 39.837 4.5 23.497M35.84 8.163c10.214 6.126 10.214 24.504 0 30.63");
}

</style>
