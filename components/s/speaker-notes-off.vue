<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll0ch_ive"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-notes-off" /></template>
<style>
.ll0ch_ive {
  fill: currentColor;
  d: path("M20.5 23.3L15.15 18H6l-4 4V4.5h2.5L11 11H8.2L.7 3.5l1.4-1.4l19.8 19.8zm.2-5.45L13.85 11H18V9h-6.15l-1-1H18V6h-8v1.15L4.85 2H20q.825 0 1.413.588T22 4v12q0 .65-.363 1.138t-.937.712M7.713 13.712Q8 13.426 8 13t-.288-.712T7 12t-.712.288T6 13t.288.713T7 14t.713-.288m0-3Q8 10.426 8 10t-.288-.712T7 9t-.712.288T6 10t.288.713T7 11t.713-.288");
}

</style>
