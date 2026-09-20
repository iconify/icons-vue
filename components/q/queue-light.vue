<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bykztlz8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:queue-light" /></template>
<style>
.bykztlz8l {
  fill: currentColor;
  d: path("M34 64a6 6 0 0 1 6-6h176a6 6 0 0 1 0 12H40a6 6 0 0 1-6-6m102 58H40a6 6 0 0 0 0 12h96a6 6 0 0 0 0-12m0 64H40a6 6 0 0 0 0 12h96a6 6 0 0 0 0-12m110-26a6 6 0 0 1-2.82 5.09l-64 40A6 6 0 0 1 170 200v-80a6 6 0 0 1 9.18-5.09l64 40A6 6 0 0 1 246 160m-17.32 0L182 130.83v58.34Z");
}

</style>
