<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h76irkb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proxima" /></template>
<style>
.h76irkb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.079 6.64c.518.079 23.763-.04 23.763-.04L42.5 17.973l-6.658 11.893H12.278L5.5 41.4h11.563l13.516-23.108l-11.403-.04l-7.097-11.614Z");
}

</style>
