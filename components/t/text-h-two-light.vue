<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="txi5v5fqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-h-two-light" /></template>
<style>
.txi5v5fqm {
  fill: currentColor;
  d: path("M150 56v120a6 6 0 0 1-12 0v-54H46v54a6 6 0 0 1-12 0V56a6 6 0 0 1 12 0v54h92V56a6 6 0 0 1 12 0m90 146h-36l36-47.95A30 30 0 1 0 187.71 126a6 6 0 1 0 11.29 4a18 18 0 0 1 14.47-11.82a18 18 0 0 1 16.87 28.66L187.2 204.4a6 6 0 0 0 4.8 9.6h48a6 6 0 0 0 0-12");
}

</style>
