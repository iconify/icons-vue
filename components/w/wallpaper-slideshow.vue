<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiuqcab_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wallpaper-slideshow" /></template>
<style>
.kiuqcab_a {
  fill: currentColor;
  d: path("M16.288 7.713Q16 7.425 16 7t.288-.712T17 6t.713.288T18 7t-.288.713T17 8t-.712-.288M9 14l2.7-3.5l1.55 2l2.3-3L19 14zm-5 8q-.825 0-1.412-.587T2 20V6h2v14h14v2zM6 9.375V4q0-.825.588-1.412T8 2h5v2H8v5.375zM8 18q-.825 0-1.412-.587T6 16v-4.625h2V16h5v2zm7 0v-2h5v-4.625h2V16q0 .825-.587 1.413T20 18zm5-8.625V4h-5V2h5q.825 0 1.413.588T22 4v5.375z");
}

</style>
