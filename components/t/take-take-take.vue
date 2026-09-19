<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lxicmcbfb"/><path class="y05gz3bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:take-take-take" /></template>
<style>
.lxicmcbfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.096 11.387v25.298L23.984 44.5l12.92-7.746V11.278L24.007 3.5z");
}

.y05gz3bot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.096 24.037L24 16.192l12.904 7.825L24 31.942z");
}

</style>
