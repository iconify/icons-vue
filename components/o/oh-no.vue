<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="byngv_uhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oh-no" /></template>
<style>
.byngv_uhh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M22.5 14A8.5 8.5 0 1 1 14 5.5a8.5 8.5 0 0 1 8.5 8.5Zm20 0A8.5 8.5 0 1 1 34 5.5a8.5 8.5 0 0 1 8.5 8.5Zm0 20a8.5 8.5 0 1 1-8.5-8.5a8.5 8.5 0 0 1 8.5 8.5Z");
}

</style>
