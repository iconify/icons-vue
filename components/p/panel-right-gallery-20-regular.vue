<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i5p7khq3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-gallery-20-regular" /></template>
<style>
.i5p7khq3y {
  fill: currentColor;
  d: path("M18 6a3 3 0 0 0-3-3H5a3 3 0 0 0-3 3v7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3zm-1 5h-4V8h4zm-4 1h4v1a2 2 0 0 1-2 2h-2zm4-6v1h-4V4h2a2 2 0 0 1 2 2m-5-2v11H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2z");
}

</style>
