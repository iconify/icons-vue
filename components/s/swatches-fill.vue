<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t4l510b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:swatches-fill" /></template>
<style>
.t4l510b2u {
  fill: currentColor;
  d: path("M240 155.91a16 16 0 0 0-1-5.22l-19.06-52.21A16 16 0 0 0 199.49 89l-67.81 24.57l12.08-69A16 16 0 0 0 130.84 26l-54.67-9.75a15.94 15.94 0 0 0-18.47 13l-25 143.12A43.82 43.82 0 0 0 75.78 224H224a16 16 0 0 0 16-16ZM76 196a16 16 0 1 1 16-16a16 16 0 0 1-16 16m42.72-8.38l9.78-55.92l76.42-27.7L224 156.11L116.78 195a45 45 0 0 0 1.94-7.38M224 208h-96.26L224 173.11Z");
}

</style>
