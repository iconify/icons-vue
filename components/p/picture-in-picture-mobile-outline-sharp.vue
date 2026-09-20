<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4047eylx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-mobile-outline-sharp" /></template>
<style>
.k4047eylx {
  fill: currentColor;
  d: path("M19 21H5V3h14zm-1-1V4H6v16zm0-16H6zm-1.038 8.692V5h-5.693v7.692zm-1-1h-3.693V6h3.692z");
}

</style>
