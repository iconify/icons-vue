<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1425ab1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-5-outline-rounded" /></template>
<style>
.y1425ab1r {
  fill: currentColor;
  d: path("M7.288 16.713Q7 16.425 7 16V9H6q-.425 0-.712-.288T5 8t.288-.712T6 7h1q.825 0 1.413.588T9 9v7q0 .425-.288.713T8 17t-.712-.288M14 17q-.425 0-.712-.288T13 16t.288-.712T14 15h3v-2h-2q-.825 0-1.412-.587T13 11V9q0-.825.588-1.412T15 7h3q.425 0 .713.288T19 8t-.288.713T18 9h-3v2h2q.825 0 1.413.588T19 13v2q0 .825-.587 1.413T17 17zm-3.713-.288Q10 16.426 10 16t.288-.712T11 15t.713.288T12 16t-.288.713T11 17t-.712-.288");
}

</style>
