<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yd8ry_b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shuffle-simple-fill" /></template>
<style>
.yd8ry_b9d {
  fill: currentColor;
  d: path("M216 48v40a8 8 0 0 1-13.66 5.66L188 79.31L156.28 111A8 8 0 0 1 145 99.72L176.69 68l-14.35-14.34A8 8 0 0 1 168 40h40a8 8 0 0 1 8 8m-4.94 112.61a8 8 0 0 0-8.72 1.73L188 176.69L53.66 42.34a8 8 0 0 0-11.32 11.32L176.69 188l-14.35 14.34A8 8 0 0 0 168 216h40a8 8 0 0 0 8-8v-40a8 8 0 0 0-4.94-7.39M99.72 145l-57.38 57.34a8 8 0 0 0 11.32 11.32L111 156.28A8 8 0 0 0 99.72 145");
}

</style>
