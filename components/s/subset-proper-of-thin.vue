<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m1215f0mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subset-proper-of-thin" /></template>
<style>
.m1215f0mu {
  fill: currentColor;
  d: path("M204 208a4 4 0 0 1-4 4h-72a84 84 0 0 1 0-168h72a4 4 0 0 1 0 8h-72a76 76 0 0 0 0 152h72a4 4 0 0 1 4 4");
}

</style>
