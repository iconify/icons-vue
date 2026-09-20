<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itr0x78ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reset-tv-outline-rounded" /></template>
<style>
.itr0x78ga {
  fill: currentColor;
  d: path("M9 21q-.425 0-.712-.288T8 20v-1H4q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v2q0 .425-.288.713T21 8t-.712-.288T20 7V5H4v12h16v-5h-7.2l1.15 1.15q.275.275.275.7t-.275.7t-.7.275t-.7-.275L9.7 11.7q-.3-.3-.3-.7t.3-.7l2.85-2.85q.275-.275.7-.275t.7.275t.275.7t-.275.7L12.8 10H20q.825 0 1.413.588T22 12v5q0 .825-.587 1.413T20 19h-4v1q0 .425-.288.713T15 21zm4-10");
}

</style>
