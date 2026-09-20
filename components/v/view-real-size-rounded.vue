<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8dxnqvdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-real-size-rounded" /></template>
<style>
.u8dxnqvdp {
  fill: currentColor;
  d: path("M7.288 16.713Q7 16.425 7 16V9H6q-.425 0-.712-.288T5 8t.288-.712T6 7h1.5q.625 0 1.063.438T9 8.5V16q0 .425-.288.713T8 17t-.712-.288m9 0Q16 16.426 16 16V9h-1q-.425 0-.712-.288T14 8t.288-.712T15 7h1.5q.625 0 1.063.438T18 8.5V16q0 .425-.288.713T17 17t-.712-.288m-5-4Q11 12.425 11 12t.288-.712T12 11t.713.288T13 12t-.288.713T12 13t-.712-.288m0 4Q11 16.426 11 16t.288-.712T12 15t.713.288T13 16t-.288.713T12 17t-.712-.288");
}

</style>
