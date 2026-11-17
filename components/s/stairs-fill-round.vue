<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2wevrpnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stairs-fill-round" /></template>
<style>
.c2wevrpnt {
  fill: currentColor;
  d: path("M5 16a1 1 0 0 0 1-1v-2a1 1 0 0 1 1-1h2a.997.997 0 0 0 1-1V9a1 1 0 0 1 1-1h2a.997.997 0 0 0 1-1V5a1 1 0 0 1 1-1h4a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-2a1 1 0 0 1 1-1Z");
}

</style>
