<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d3m1bwf4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toom" /></template>
<style>
.d3m1bwf4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.786 8.679l-8.357 30.643H4.5l6.964-23.68zm4.178 0L43.5 15.643l-6.964 23.679H22.607z");
}

</style>
