<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xp42h2bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unite-students" /></template>
<style>
.xp42h2bqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.568 39.417h34.864M24 42.5v-3.083M6.568 15.572v12.226a7.542 7.542 0 0 0 15.083 0V15.572m5.155 15.681c1.391 3.136 4.731 4.086 7.167 4.086a7.46 7.46 0 0 0 0-14.92h-.17a7.454 7.454 0 0 1-7.453-7.453A7.466 7.466 0 0 1 33.814 5.5c2.436 0 5.776.95 7.167 4.086");
}

</style>
