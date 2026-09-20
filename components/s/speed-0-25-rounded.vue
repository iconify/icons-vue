<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0yleg6np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-25-rounded" /></template>
<style>
.q0yleg6np {
  fill: currentColor;
  d: path("M15 17q-.425 0-.712-.288T14 16t.288-.712T15 15h3v-2h-3q-.425 0-.712-.288T14 12V8q0-.425.288-.712T15 7h4q.425 0 .713.288T20 8t-.288.713T19 9h-3v2h2q.825 0 1.413.588T20 13v2q0 .825-.587 1.413T18 17zm-3 0H8q-.425 0-.712-.288T7 16v-3q0-.825.588-1.412T9 11h2V9H8q-.425 0-.712-.288T7 8t.288-.712T8 7h3q.825 0 1.413.588T13 9v2q0 .825-.587 1.413T11 13H9v2h3q.425 0 .713.288T13 16t-.288.713T12 17m-7.712-.288Q4 16.426 4 16t.288-.712T5 15t.713.288T6 16t-.288.713T5 17t-.712-.288");
}

</style>
