<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y_4qawb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-away-20-filled" /></template>
<style>
.y_4qawb-y {
  fill: currentColor;
  d: path("M10 20c5.523 0 10-4.477 10-10S15.523 0 10 0S0 4.477 0 10s4.477 10 10 10m0-13.992v3.578l2.707 2.707a1 1 0 0 1-1.414 1.415l-3-3A1 1 0 0 1 8 10V6.008a1 1 0 1 1 2 0");
}

</style>
