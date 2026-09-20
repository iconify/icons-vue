<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u5v92zxlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shuffle-simple-thin" /></template>
<style>
.u5v92zxlz {
  fill: currentColor;
  d: path("M212 48v40a4 4 0 0 1-8 0V57.66l-50.54 50.54a4 4 0 1 1-5.66-5.66L198.34 52H168a4 4 0 0 1 0-8h40a4 4 0 0 1 4 4m-4 116a4 4 0 0 0-4 4v30.34L50.83 45.17a4 4 0 0 0-5.66 5.66L198.34 204H168a4 4 0 0 0 0 8h40a4 4 0 0 0 4-4v-40a4 4 0 0 0-4-4m-105.46-16.2l-57.37 57.37a4 4 0 0 0 5.66 5.66l57.37-57.37a4 4 0 1 0-5.66-5.66");
}

</style>
