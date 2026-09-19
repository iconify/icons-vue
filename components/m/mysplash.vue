<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8g1bdcbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mysplash" /></template>
<style>
.e8g1bdcbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 35.29L24 24l-6.5 11.29h-13l13-22.58L24 24l6.5-11.29l13 22.58Z");
}

</style>
