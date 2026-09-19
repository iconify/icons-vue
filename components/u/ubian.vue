<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8kljqb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ubian" /></template>
<style>
.k8kljqb1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.162 10.483L28.9 23.223a8.25 8.25 0 0 1 .15 11.506L16.467 22.145H4.5l12.739 12.741a8.25 8.25 0 0 0 7.967 2.135a8.24 8.24 0 0 0 3.845-2.29l.371.37a8.244 8.244 0 0 0 13.797-3.698a8.24 8.24 0 0 0-2.135-7.964L28.13 10.483z");
}

</style>
