<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hncob1bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nokia-wireless" /></template>
<style>
.hncob1bwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 11c7.18 0 13 5.82 13 13s-5.82 13-13 13zm-13 0c7.18 0 13 5.82 13 13s-5.82 13-13 13zm-13 0c7.18 0 13 5.82 13 13s-5.82 13-13 13z");
}

</style>
