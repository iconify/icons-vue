<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag2pjy3mn"/><path class="xa7tlw86o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-speed" /></template>
<style>
.ag2pjy3mn {
  fill: currentColor;
  d: path("m20.39 8.56l-1.24 1.86a8 8 0 0 1-.22 7.58H5.07A8 8 0 0 1 15.58 6.85l1.86-1.24A10 10 0 0 0 4 20h16a10 10 0 0 0 .38-11.44z");
}

.xa7tlw86o {
  fill: currentColor;
  d: path("M10.59 15.41a2 2 0 0 0 2.83 0l5.66-8.49l-8.49 5.66a2 2 0 0 0 0 2.83");
}

</style>
