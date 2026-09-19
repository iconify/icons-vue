<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ptsu9bb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:to-do-list" /></template>
<style>
.ptsu9bb-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 26.059l13.717 13.619L43.5 15.21l-6.11-6.888l-19.173 18.982l-7.328-7.25z");
}

</style>
