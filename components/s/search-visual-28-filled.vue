<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nkg-v2bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-visual-28-filled" /></template>
<style>
.nkg-v2bcj {
  fill: currentColor;
  d: path("M4 16.5a1 1 0 0 1 1 1V21a2 2 0 0 0 2 2h3.5a1 1 0 1 1 0 2H7a4 4 0 0 1-4-4v-3.5a1 1 0 0 1 1-1m20 0a1 1 0 0 1 1 1V21a4 4 0 0 1-4 4h-3.5a1 1 0 1 1 0-2H21a2 2 0 0 0 2-2v-3.5a1 1 0 0 1 1-1M14 10a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-3.5-9a1 1 0 1 1 0 2H7a2 2 0 0 0-2 2v3.5a1 1 0 1 1-2 0V7a4 4 0 0 1 4-4zM21 3a4 4 0 0 1 4 4v3.5a1 1 0 1 1-2 0V7a2 2 0 0 0-2-2h-3.5a1 1 0 1 1 0-2zM8.5 7a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
