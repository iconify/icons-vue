<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvoilfr0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-kanban-rounded" /></template>
<style>
.fvoilfr0k {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM7.288 7.288Q7 7.575 7 8v8q0 .425.288.713T8 17t.713-.288T9 16V8q0-.425-.288-.712T8 7t-.712.288m8 0Q15 7.575 15 8v6q0 .425.288.713T16 15t.713-.288T17 14V8q0-.425-.288-.712T16 7t-.712.288m-4 0Q11 7.575 11 8v3q0 .425.288.713T12 12t.713-.288T13 11V8q0-.425-.288-.712T12 7t-.712.288");
}

</style>
