<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="esyuc0b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-32-regular" /></template>
<style>
.esyuc0b5r {
  fill: currentColor;
  d: path("M23.5 2A4.5 4.5 0 0 1 28 6.5v19a4.5 4.5 0 0 1-4.5 4.5h-15a4.5 4.5 0 0 1-4.494-4.269L4 25.5v-19A4.5 4.5 0 0 1 8.5 2zm-15 2A2.5 2.5 0 0 0 6 6.5v19l.013.256A2.5 2.5 0 0 0 8.5 28h15a2.5 2.5 0 0 0 2.5-2.5v-19A2.5 2.5 0 0 0 23.5 4zm3.5 9.003c0-1.554 1.695-2.514 3.028-1.715l4.998 2.997c1.295.777 1.295 2.653 0 3.43l-4.998 2.997c-1.333.8-3.028-.16-3.028-1.715z");
}

</style>
