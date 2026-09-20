<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kx6fd8bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:split-vertical-thin" /></template>
<style>
.kx6fd8bek {
  fill: currentColor;
  d: path("M212 152a4 4 0 0 1-4 4h-76v66.34l25.17-25.17a4 4 0 0 1 5.66 5.66l-32 32a4 4 0 0 1-5.66 0l-32-32a4 4 0 0 1 5.66-5.66L124 222.34V156H48a4 4 0 0 1 0-8h160a4 4 0 0 1 4 4M48 108h160a4 4 0 0 0 0-8h-76V33.66l25.17 25.17a4 4 0 1 0 5.66-5.66l-32-32a4 4 0 0 0-5.66 0l-32 32a4 4 0 0 0 5.66 5.66L124 33.66V100H48a4 4 0 0 0 0 8");
}

</style>
