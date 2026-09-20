<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="udnn_c6vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:meteor-thin" /></template>
<style>
.udnn_c6vf {
  fill: currentColor;
  d: path("M96 124a36 36 0 1 0 36 36a36 36 0 0 0-36-36m0 64a28 28 0 1 1 28-28a28 28 0 0 1-28 28m122.83-62.83a4 4 0 0 1 0 5.66l-48 48a4 4 0 0 1-5.66-5.66l48-48a4 4 0 0 1 5.66 0m-32-18.34l-24 24a4 4 0 0 1-5.66-5.66l24-24a4 4 0 1 1 5.66 5.66m40-40l-16 16a4 4 0 0 1-5.66-5.66l16-16a4 4 0 1 1 5.66 5.66M125.17 93.17l72-72a4 4 0 1 1 5.66 5.66l-72 72a4 4 0 1 1-5.66-5.66m18.91 109.26a4 4 0 0 1 0 5.65a68 68 0 1 1-96.16-96.16l82.74-82.75a4 4 0 1 1 5.66 5.66l-82.75 82.74a60 60 0 0 0 84.86 84.86a4 4 0 0 1 5.65 0");
}

</style>
