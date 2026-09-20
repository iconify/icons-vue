<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bqy86gtbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:prohibit-inset" /></template>
<style>
.bqy86gtbo {
  fill: currentColor;
  d: path("M165.66 154.34a8 8 0 0 1-11.32 11.32l-64-64a8 8 0 0 1 11.32-11.32ZM232 128A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104m-16 0a88 88 0 1 0-88 88a88.1 88.1 0 0 0 88-88");
}

</style>
