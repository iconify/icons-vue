<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-5e-6bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-play-arrow" /></template>
<style>
.w-5e-6bny {
  fill: currentColor;
  d: path("M10 8.64L15.27 12L10 15.36zM8 5v14l11-7z");
}

</style>
