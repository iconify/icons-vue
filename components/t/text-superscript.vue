<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="peldz5bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-superscript" /></template>
<style>
.peldz5bxv {
  fill: currentColor;
  d: path("M248 144a8 8 0 0 1-8 8h-48a8 8 0 0 1-6.4-12.8l43.17-57.55a16 16 0 1 0-27.86-15a8 8 0 0 1-15.09-5.33a32 32 0 1 1 55.74 29.92L208 136h32a8 8 0 0 1 8 8m-98.76-70a8 8 0 0 0-11.29.8L92 127.79l-45.95-53A8 8 0 0 0 34 85.24L81.41 140L34 194.76a8 8 0 0 0 12.1 10.48l46-53l45.95 53a8 8 0 1 0 12.1-10.48L102.59 140l47.46-54.76a8 8 0 0 0-.81-11.24");
}

</style>
