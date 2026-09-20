<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1vm9ib-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:oven-gen-outline" /></template>
<style>
.z1vm9ib-m {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-9v7h14v-7h-2v5H7v-5zm4 3h6v-3H9zm-4-5h14V5H5zm2.288-2.287Q7 7.425 7 7t.288-.712T8 6t.713.288T9 7t-.288.713T8 8t-.712-.288m4 0Q11 7.426 11 7t.288-.712T12 6t.713.288T13 7t-.288.713T12 8t-.712-.288m4 0Q15 7.426 15 7t.288-.712T16 6t.713.288T17 7t-.288.713T16 8t-.712-.288");
}

</style>
