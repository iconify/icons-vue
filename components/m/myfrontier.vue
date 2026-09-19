<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hf7hzjbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myfrontier" /></template>
<style>
.hf7hzjbes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24A18.5 18.5 0 1 0 24 5.5H5.5m12.333 6.166H5.5m0 6.166h6.167");
}

</style>
