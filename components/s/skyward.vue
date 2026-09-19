<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7rfnlbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skyward" /></template>
<style>
.l7rfnlbkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.713 32c5.103-6.418 11.598-11.407 24.135-11.407H43.5M9.97 32c6.035-7.005 14.224-13.763 29.174-13.763H43.5M4.5 32c7.392-8.075 16.732-16 33.976-16H43.5");
}

</style>
