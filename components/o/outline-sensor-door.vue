<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1ibl_m3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sensor-door" /></template>
<style>
.i1ibl_m3k {
  fill: currentColor;
  d: path("M18 4v16H6V4zm0-2H6c-1.1 0-2 .9-2 2v18h16V4c0-1.1-.9-2-2-2m-2.5 8.5c-.83 0-1.5.67-1.5 1.5s.67 1.5 1.5 1.5S17 12.83 17 12s-.67-1.5-1.5-1.5");
}

</style>
