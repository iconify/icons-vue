<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3us77y1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:oven-outline" /></template>
<style>
.n3us77y1r {
  fill: currentColor;
  d: path("M16.713 6.713Q17 6.425 17 6t-.288-.712T16 5t-.712.288T15 6t.288.713T16 7t.713-.288m-4 0Q13 6.426 13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7t.713-.288m-4 0Q9 6.426 9 6t-.288-.712T8 5t-.712.288T7 6t.288.713T8 7t.713-.288M5 10v9h14v-9zm5 4h4v-2h-4zm-5 7q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm7-11");
}

</style>
