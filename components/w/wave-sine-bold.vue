<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tz12zb3ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wave-sine-bold" /></template>
<style>
.tz12zb3ix {
  fill: currentColor;
  d: path("M242.86 133.1c-23 49-43 70.9-64.82 70.9c-27.64 0-43.8-34.44-60.9-70.9c-7.14-15.32-14.61-31.1-22.22-42.37C88.39 81.09 82.53 76 78 76c-3.82 0-18.24 4.12-43.09 57.1a12 12 0 0 1-21.73-10.2c23-49 43-70.9 64.82-70.9c27.64 0 43.8 34.44 60.9 70.9c7.19 15.32 14.61 31.15 22.22 42.37c6.53 9.64 12.39 14.73 17 14.73c3.82 0 18.24-4.12 43.09-57.1a12 12 0 0 1 21.73 10.2Z");
}

</style>
