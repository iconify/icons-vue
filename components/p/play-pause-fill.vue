<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nma-7qsex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:play-pause-fill" /></template>
<style>
.nma-7qsex {
  fill: currentColor;
  d: path("M184 64v128a8 8 0 0 1-16 0V64a8 8 0 0 1 16 0m40-8a8 8 0 0 0-8 8v128a8 8 0 0 0 16 0V64a8 8 0 0 0-8-8m-87.33 58.66L48.48 58.51A15.91 15.91 0 0 0 24 71.85v112.3A15.83 15.83 0 0 0 32.23 198a15.95 15.95 0 0 0 16.25-.53l88.19-56.15a15.8 15.8 0 0 0 0-26.68Z");
}

</style>
