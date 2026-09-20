<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgbcscary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:manga-sharp" /></template>
<style>
.qgbcscary {
  fill: currentColor;
  d: path("M2 20V4h20v16zm6.1-2H20V7.025L17 8l-3.075-1L12 9.625l-3.075 1v3.25l-1.9 2.625z");
}

</style>
