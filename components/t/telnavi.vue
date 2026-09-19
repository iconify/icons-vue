<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxgx7qbbh"/><path class="bv0-wtb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telnavi" /></template>
<style>
.bv0-wtb4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 4.5l8.25 4v35");
}

.zxgx7qbbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5v-39s-8.125 6.949-15.5 6.949v32.05h31v-21l-7.25-6");
}

</style>
