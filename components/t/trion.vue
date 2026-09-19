<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gbdm1o_zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trion" /></template>
<style>
.gbdm1o_zo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.5H9.07L22 3.035a4 4 0 0 1 4 0l15.156 8.75a4 4 0 0 1 2 3.465v1.5H4.844m30.734 13h7.578v3a4 4 0 0 1-2 3.465L28 43.81V23.5h15.156M20 43.81V23.5H4.844v9.25a4 4 0 0 0 2 3.465l8.104 4.678V29.75H9.896");
}

</style>
