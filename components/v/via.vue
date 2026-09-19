<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qwbyixbjr"/><path class="k_zpez8ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:via" /></template>
<style>
.k_zpez8ik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.97 22l.34-8.54l-6.14 1.08L4.5 31.73M25.37 7.75l6 32.5l12.13-2.67l-9.61-29.32z");
}

.qwbyixbjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 31.73L25.37 7.75l1.65 8.96l-14.79 18.2z");
}

</style>
