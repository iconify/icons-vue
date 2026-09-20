<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rstol_bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-24-filled" /></template>
<style>
.rstol_bhj {
  fill: currentColor;
  d: path("M14.75 20.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5zm2.75-3a.75.75 0 0 1 0 1.5h-11a.75.75 0 0 1 0-1.5zm1-3a.75.75 0 0 1 0 1.5h-13a.75.75 0 0 1 0-1.5zM11.47 2.22a.75.75 0 0 1 1.06 0c.404.403 2 2.128 3.5 4.362c1.245 1.856 2.496 4.171 2.86 6.418H5.11c.364-2.247 1.614-4.562 2.86-6.418c1.5-2.234 3.096-3.959 3.5-4.362");
}

</style>
