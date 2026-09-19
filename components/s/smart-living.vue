<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s2yetn1-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-living" /></template>
<style>
.s2yetn1-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.02 26.218l-3.325 2.747V43.5l5.414-4.54h8.986V15.244L24 4.5L7.905 15.244V38.96h10.97");
}

</style>
