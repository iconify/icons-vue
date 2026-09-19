<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aachven2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:progressbar95" /></template>
<style>
.aachven2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 20.051h41v7.897h-41zm5.965 0v7.898m5.965-7.898v7.898m5.965-7.898v7.898");
}

</style>
