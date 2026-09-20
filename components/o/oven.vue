<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltdv1kbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:oven" /></template>
<style>
.ltdv1kbqd {
  fill: currentColor;
  d: path("M3 9V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v4zm2 12q-.825 0-1.412-.587T3 19v-9h18v9q0 .825-.587 1.413T19 21zM8.713 6.712Q9 6.425 9 6t-.288-.712T8 5t-.712.288T7 6t.288.713T8 7t.713-.288M10 14h4v-2h-4zm2.713-7.288Q13 6.426 13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7t.713-.288m4 0Q17 6.426 17 6t-.288-.712T16 5t-.712.288T15 6t.288.713T16 7t.713-.288");
}

</style>
