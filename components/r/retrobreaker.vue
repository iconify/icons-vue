<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-sqpjb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:retrobreaker" /></template>
<style>
.a-sqpjb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.35 39.92h13.63v2.58H17.35zm10.59-17.4h2.92v2.92h-2.92zM11.67 5.5v13.35M5.5 5.5v13.35M17.83 5.5v13.35M24 5.5v13.35M30.17 5.5v13.35M36.33 5.5v13.35M42.5 5.5v13.35M5.5 8.17h37m-37 2.67h37m-37 2.67h37m-37 2.67h37M5.5 5.5h37M11.67 18.85H5.5m12.33 0H42.5");
}

</style>
