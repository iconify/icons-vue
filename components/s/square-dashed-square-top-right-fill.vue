<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7nzo1exz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-fill" /></template>
<style>
.f7nzo1exz {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0Zm7 0a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3Zm-7 5a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Zm3 12a3 3 0 0 1-3-3v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2Zm17-3a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0Zm-12 1h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
