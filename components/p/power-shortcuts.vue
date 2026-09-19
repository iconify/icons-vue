<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lst03lj-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:power-shortcuts" /></template>
<style>
.lst03lj-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24L27.629 8.129v10.497H7.142L4.5 29.374h23.129v10.497zm-31.175-5.374L9.683 29.374m7.825-10.748l-2.641 10.748");
}

</style>
