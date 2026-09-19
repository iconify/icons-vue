<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4q8ppklg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shutterstock" /></template>
<style>
.j4q8ppklg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.243 10.824V24h7.379V13.987c0-1.165.943-2.109 2.108-2.109h5.112V4.5h-8.274a6.324 6.324 0 0 0-6.325 6.324m29.514 26.352V24h-7.379v10.014a2.11 2.11 0 0 1-2.108 2.108h-5.112V43.5h8.274a6.324 6.324 0 0 0 6.325-6.324");
}

</style>
