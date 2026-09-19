<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v_jcb1-sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rimusic" /></template>
<style>
.v_jcb1-sa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.674 5.5v37m-22.887-8.962L33.02 25.32a1.525 1.525 0 0 0 0-2.642L8.613 8.588a1.525 1.525 0 0 0-2.287 1.32v28.184a1.525 1.525 0 0 0 2.287 1.32l6.3-3.637");
}

</style>
