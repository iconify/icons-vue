<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="prtis2bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:union-bold" /></template>
<style>
.prtis2bxt {
  fill: currentColor;
  d: path("M212 64v80a84 84 0 0 1-168 0V64a12 12 0 0 1 24 0v80a60 60 0 0 0 120 0V64a12 12 0 0 1 24 0");
}

</style>
