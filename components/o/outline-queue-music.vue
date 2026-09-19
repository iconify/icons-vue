<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekrn35e4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-queue-music" /></template>
<style>
.ekrn35e4r {
  fill: currentColor;
  d: path("M22 6h-5v8.18c-.31-.11-.65-.18-1-.18c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3V8h3zm-7 0H3v2h12zm0 4H3v2h12zm-4 4H3v2h8z");
}

</style>
