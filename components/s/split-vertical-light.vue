<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v85jmnbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:split-vertical-light" /></template>
<style>
.v85jmnbxu {
  fill: currentColor;
  d: path("M214 152a6 6 0 0 1-6 6h-74v59.51l21.76-21.75a6 6 0 0 1 8.48 8.48l-32 32a6 6 0 0 1-8.48 0l-32-32a6 6 0 0 1 8.48-8.48L122 217.51V158H48a6 6 0 0 1 0-12h160a6 6 0 0 1 6 6M48 110h160a6 6 0 0 0 0-12h-74V38.49l21.76 21.75a6 6 0 0 0 8.48-8.48l-32-32a6 6 0 0 0-8.48 0l-32 32a6 6 0 0 0 8.48 8.48L122 38.49V98H48a6 6 0 0 0 0 12");
}

</style>
