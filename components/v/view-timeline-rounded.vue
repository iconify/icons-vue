<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3wwlcb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-timeline-rounded" /></template>
<style>
.l3wwlcb5p {
  fill: currentColor;
  d: path("M7 17h4q.425 0 .713-.288T12 16t-.288-.712T11 15H7q-.425 0-.712.288T6 16t.288.713T7 17m3-4h4q.425 0 .713-.288T15 12t-.288-.712T14 11h-4q-.425 0-.712.288T9 12t.288.713T10 13m3-4h4q.425 0 .713-.288T18 8t-.288-.712T17 7h-4q-.425 0-.712.288T12 8t.288.713T13 9M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
