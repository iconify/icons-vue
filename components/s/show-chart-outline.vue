<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z27n62b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:show-chart-outline" /></template>
<style>
.z27n62b6e {
  fill: currentColor;
  d: path("M3.5 18.5L2 17l7.5-7.5l4 4l7.1-8L22 6.9l-8.5 9.6l-4-4z");
}

</style>
