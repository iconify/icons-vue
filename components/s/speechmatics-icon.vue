<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":308};
const content = `<path class="z23yfvy3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:speechmatics-icon" /></template>
<style>
.z23yfvy3q {
  fill: var(--svg-color--0d3c48, #0d3c48);
  d: path("M211.394 71.564c-12.682-11.445-26.85-19.983-41.883-25.798l14.167-36.81C132.95-10.53 73.311 1.966 34.77 44.652C18.747 62.408 8.353 83.256 3.404 104.971c-10.579 46.213 3.588 96.633 41.264 130.597a135.3 135.3 0 0 0 42.068 25.86l-14.167 36.87c50.667 19.364 110.181 6.93 148.661-35.82c16.023-17.754 26.417-38.541 31.366-60.317c10.579-46.214-3.588-96.633-41.264-130.597zm-28.52 156.147c-23.756 26.354-60.442 34.026-91.745 22.21a83 83 0 0 1-26.231-16.086c-34.273-30.87-36.995-83.703-6.125-117.976c23.88-26.478 60.875-34.15 92.24-21.962a84.2 84.2 0 0 1 25.737 15.837c34.273 30.871 36.995 83.704 6.124 117.977");
}

</style>
