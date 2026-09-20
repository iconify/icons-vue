<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li81dsm1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:p2p-rounded" /></template>
<style>
.li81dsm1j {
  fill: currentColor;
  d: path("M3 20q-.825 0-1.412-.587T1 18V4q0-.825.588-1.412T3 2h6q.825 0 1.413.588T11 4v4q0 .425-.288.713T10 9H8q-1.25 0-2.125.875T5 12t.875 2.125T8 15h2q.425 0 .713.288T11 16v2q0 .825-.587 1.413T9 20zM6.538 6.288q.212-.213.212-.538t-.213-.537T6 5t-.537.213t-.213.537t.213.538T6 6.5t.538-.213m.75 6.426Q7 12.425 7 12t.288-.712T8 11t.713.288T9 12t-.288.713T8 13t-.712-.288m4 0Q11 12.426 11 12t.288-.712T12 11t.713.288T13 12t-.288.713T12 13t-.712-.288M15 22q-.825 0-1.412-.587T13 20v-4q0-.425.288-.712T14 15h2q1.25 0 2.125-.875T19 12t-.875-2.125T16 9h-2q-.425 0-.712-.288T13 8V6q0-.825.588-1.412T15 4h6q.825 0 1.413.588T23 6v14q0 .825-.587 1.413T21 22zm.288-9.287Q15 12.425 15 12t.288-.712T16 11t.713.288T17 12t-.288.713T16 13t-.712-.288m3.25-4.424q.212-.213.212-.538t-.213-.537T18 7t-.537.213t-.213.537t.213.538T18 8.5t.538-.213");
}

</style>
