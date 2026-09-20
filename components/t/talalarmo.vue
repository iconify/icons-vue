<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nh7aynbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:talalarmo" /></template>
<style>
.nh7aynbgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.23 11.22A22.6 22.6 0 0 1 16.92 4.5m14.16 0a22.6 22.6 0 0 1 10.69 6.72M24 8.76zA17.37 17.37 0 1 1 6.63 26.13A17.35 17.35 0 0 1 24 8.76m-.03 17.37V16.11m9.5 18.02l-9.5-8");
}

</style>
