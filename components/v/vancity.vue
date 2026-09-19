<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l6biy24pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vancity" /></template>
<style>
.l6biy24pq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.336 43.5c10.988-9.99 13.32-25.855 13.32-39h-8.818c0 10.977-1.191 22.5-7.838 30.558C17.354 27 16.162 15.478 16.162 4.5H7.345c0 13.145 2.33 29.01 13.32 39z");
}

</style>
