<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-oqgfb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wallpaper-slideshow-outline-sharp" /></template>
<style>
.w-oqgfb5p {
  fill: currentColor;
  d: path("M16.288 7.713Q16 7.425 16 7t.288-.712T17 6t.713.288T18 7t-.288.713T17 8t-.712-.288M9 14l2.7-3.5l1.55 2l2.3-3L19 14zm-7 8V6h2v14h14v2zM6 9.375V2h7v2H8v5.375zM6 18v-6.625h2V16h5v2zm9 0v-2h5v-4.625h2V18zm5-8.625V4h-5V2h7v7.375z");
}

</style>
