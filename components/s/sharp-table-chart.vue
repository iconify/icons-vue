<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4wevifyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-table-chart" /></template>
<style>
.e4wevifyn {
  fill: currentColor;
  d: path("M10 10.02h5V21h-5zM17 21h5V10h-5zm5-18H3v5h19zM3 21h5V10H3z");
}

</style>
