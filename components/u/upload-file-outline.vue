<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9afhmxuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upload-file-outline" /></template>
<style>
.g9afhmxuf {
  fill: currentColor;
  d: path("M11 19h2v-4.175l1.6 1.6L16 15l-4-4l-4 4l1.425 1.4L11 14.825zm-5 3q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm7-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
