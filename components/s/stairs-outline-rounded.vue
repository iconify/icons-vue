<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w83l3qbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stairs-outline-rounded" /></template>
<style>
.w83l3qbwy {
  fill: currentColor;
  d: path("M10.425 14.675H12q.425 0 .713-.288t.287-.712V11.35h1.575q.425 0 .713-.287t.287-.713V8H17q.425 0 .713-.287T18 7t-.288-.712T17 6h-2.425q-.425 0-.712.288T13.574 7v2.325H12q-.425 0-.712.288t-.288.712v2.325H9.425q-.425 0-.712.288t-.288.712V16H7q-.425 0-.712.288T6 17t.288.713T7 18h2.425q.425 0 .713-.288t.287-.712zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
