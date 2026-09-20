<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6bzqebcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-add-rounded" /></template>
<style>
.w6bzqebcv {
  fill: currentColor;
  d: path("M19 21h-1q-.425 0-.712-.288T17 20t.288-.712T18 19h1v-1q0-.425.288-.712T20 17t.713.288T21 18v1h1q.425 0 .713.288T23 20t-.288.713T22 21h-1v1q0 .425-.288.713T20 23t-.712-.288T19 22zM5 11q-.825 0-1.412-.587T3 9V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v4q0 .825-.587 1.413T19 11zm0 10q-.825 0-1.412-.587T3 19v-4q0-.825.588-1.412T5 13h14q.825 0 1.413.588T21 15v.1q-.225-.05-.5-.075T20 15q-2.1 0-3.55 1.463T15 20q0 .275.025.525T15.1 21z");
}

</style>
