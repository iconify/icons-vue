<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c7arqcjkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-eight-light" /></template>
<style>
.c7arqcjkd {
  fill: currentColor;
  d: path("M151.62 119.45a46 46 0 1 0-47.24 0a54 54 0 1 0 47.24 0M94 80a34 34 0 1 1 34 34a34 34 0 0 1-34-34m34 130a42 42 0 1 1 42-42a42 42 0 0 1-42 42");
}

</style>
