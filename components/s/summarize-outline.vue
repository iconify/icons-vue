<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkai3obxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:summarize-outline" /></template>
<style>
.nkai3obxu {
  fill: currentColor;
  d: path("M8.713 8.713Q9 8.425 9 8t-.288-.712T8 7t-.712.288T7 8t.288.713T8 9t.713-.288m0 4Q9 12.426 9 12t-.288-.712T8 11t-.712.288T7 12t.288.713T8 13t.713-.288m0 4Q9 16.426 9 16t-.288-.712T8 15t-.712.288T7 16t.288.713T8 17t.713-.288M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h11l5 5v11q0 .825-.587 1.413T19 21zm0-2h14V9h-4V5H5zM5 5v4zv14z");
}

</style>
