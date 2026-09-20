<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmdjx921c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:padding-outline-rounded" /></template>
<style>
.fmdjx921c {
  fill: currentColor;
  d: path("M8.713 8.713Q9 8.425 9 8t-.288-.712T8 7t-.712.288T7 8t.288.713T8 9t.713-.288m4 0Q13 8.426 13 8t-.288-.712T12 7t-.712.288T11 8t.288.713T12 9t.713-.288m4 0Q17 8.426 17 8t-.288-.712T16 7t-.712.288T15 8t.288.713T16 9t.713-.288M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
