<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lzroc5bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:replit-logo-fill" /></template>
<style>
.lzroc5bjz {
  fill: currentColor;
  d: path("M72 160h72v56a16 16 0 0 1-16 16H72a16 16 0 0 1-16-16v-40a16 16 0 0 1 16-16m56-136H72a16 16 0 0 0-16 16v40a16 16 0 0 0 16 16h72V40a16 16 0 0 0-16-16m88 72h-72v64h72a16 16 0 0 0 16-16v-32a16 16 0 0 0-16-16");
}

</style>
