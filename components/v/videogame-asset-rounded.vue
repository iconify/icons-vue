<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ys-3byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:videogame-asset-rounded" /></template>
<style>
.m-ys-3byb {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V8q0-.825.588-1.412T4 6h16q.825 0 1.413.588T22 8v8q0 .825-.587 1.413T20 18zm3-5v1q0 .425.288.713T8 15t.713-.288T9 14v-1h1q.425 0 .713-.288T11 12t-.288-.712T10 11H9v-1q0-.425-.288-.712T8 9t-.712.288T7 10v1H6q-.425 0-.712.288T5 12t.288.713T6 13zm8.563 1.563Q16 14.125 16 13.5t-.437-1.062T14.5 12t-1.062.438T13 13.5t.438 1.063T14.5 15t1.063-.437m3-3Q19 11.125 19 10.5t-.437-1.062T17.5 9t-1.062.438T16 10.5t.438 1.063T17.5 12t1.063-.437");
}

</style>
