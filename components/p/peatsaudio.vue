<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jrnbwlw1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:peatsaudio" /></template>
<style>
.jrnbwlw1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.286 13.775V5.5H7.714v10.308l32.16 8.45C37.696 32.82 32.657 38.25 24.288 42.5C14.845 39.419 7.993 29.026 7.714 24.258");
}

</style>
