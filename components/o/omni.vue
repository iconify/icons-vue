<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="enwpqvcuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omni" /></template>
<style>
.enwpqvcuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.273 22.739h13.454M5.5 16.01l4.54-6.054a1.68 1.68 0 0 1 1.346-.673h25.228c.53 0 1.028.25 1.345.673L42.5 16.01m-37 0h37m-37 0v19.341a3.364 3.364 0 0 0 3.364 3.364h30.272a3.364 3.364 0 0 0 3.364-3.364v-19.34");
}

</style>
