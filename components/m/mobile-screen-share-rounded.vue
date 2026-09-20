<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt8v2bchq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-screen-share-rounded" /></template>
<style>
.nt8v2bchq {
  fill: currentColor;
  d: path("M10 15q-.425 0-.712-.288T9 14v-.5q0-1.25.875-2.125T12 10.5h1V9.1q0-.175.15-.238t.275.063l2.225 2.225q.15.15.15.35t-.15.35l-2.225 2.225q-.125.125-.275.062T13 13.9v-1.4h-1q-.425 0-.712.287T11 13.5v.5q0 .425-.288.713T10 15m-3 8q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v18q0 .825-.587 1.413T17 23zm0-5h10V6H7z");
}

</style>
