<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc2d28bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-notes-sharp" /></template>
<style>
.dc2d28bam {
  fill: currentColor;
  d: path("M7.713 13.713Q8 13.425 8 13t-.288-.712T7 12t-.712.288T6 13t.288.713T7 14t.713-.288m0-3Q8 10.426 8 10t-.288-.712T7 9t-.712.288T6 10t.288.713T7 11t.713-.288m0-3Q8 7.426 8 7t-.288-.712T7 6t-.712.288T6 7t.288.713T7 8t.713-.288M10 14h5v-2h-5zm0-3h8V9h-8zm0-3h8V6h-8zM2 22V2h20v16H6z");
}

</style>
