<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frfi_ugfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tabs-outline-rounded" /></template>
<style>
.frfi_ugfr {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14v-7H5zm0-9h14V5H5zm12-2q.425 0 .713-.288T18 7t-.288-.712T17 6h-4q-.425 0-.712.288T12 7t.288.713T13 8zM5 10V5z");
}

</style>
