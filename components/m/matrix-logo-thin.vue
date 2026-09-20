<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sq6w9go_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:matrix-logo-thin" /></template>
<style>
.sq6w9go_t {
  fill: currentColor;
  d: path("M44 44v168h20a4 4 0 0 1 0 8H40a4 4 0 0 1-4-4V40a4 4 0 0 1 4-4h24a4 4 0 0 1 0 8Zm172-8h-24a4 4 0 0 0 0 8h20v168h-20a4 4 0 0 0 0 8h24a4 4 0 0 0 4-4V40a4 4 0 0 0-4-4m-64 56a28 28 0 0 0-24 13.6a28 28 0 0 0-44-5.17V96a4 4 0 0 0-8 0v64a4 4 0 0 0 8 0v-40a20 20 0 0 1 40 0v40a4 4 0 0 0 8 0v-40a20 20 0 0 1 40 0v40a4 4 0 0 0 8 0v-40a28 28 0 0 0-28-28");
}

</style>
