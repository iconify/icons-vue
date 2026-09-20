<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r7jshg-4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:map-trifold-thin" /></template>
<style>
.r7jshg-4l {
  fill: currentColor;
  d: path("M226.46 52.85a4 4 0 0 0-3.43-.73l-62.56 15.64l-62.68-31.34a4 4 0 0 0-2.76-.3l-64 16A4 4 0 0 0 28 56v144a4 4 0 0 0 5 3.88l62.56-15.64l62.68 31.34a4 4 0 0 0 2.76.3l64-16a4 4 0 0 0 3-3.88V56a4 4 0 0 0-1.54-3.15M100 46.47l56 28v135.06l-56-28ZM36 59.12l56-14v135.76l-56 14Zm184 137.76l-56 14V75.12l56-14Z");
}

</style>
