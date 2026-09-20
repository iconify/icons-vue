<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d06kw1b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:prohibit-inset-thin" /></template>
<style>
.d06kw1b8p {
  fill: currentColor;
  d: path("M162.83 157.17a4 4 0 0 1-5.66 5.66l-64-64a4 4 0 0 1 5.66-5.66ZM228 128A100 100 0 1 1 128 28a100.11 100.11 0 0 1 100 100m-8 0a92 92 0 1 0-92 92a92.1 92.1 0 0 0 92-92");
}

</style>
