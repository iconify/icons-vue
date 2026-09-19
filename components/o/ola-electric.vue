<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dl8-o1b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ola-electric" /></template>
<style>
.dl8-o1b1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.353 17c3.785 0 6.853 3.13 6.853 7s-3.068 7-6.853 7S4.5 27.87 4.5 24s3.068-7 6.853-7m9.002 0v14h5.728m2.149 0l7.634-14L43.5 31");
}

</style>
