<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sis8cdhag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-frame-outline-rounded" /></template>
<style>
.sis8cdhag {
  fill: currentColor;
  d: path("M6 21q-.425 0-.712-.288T5 20v-1H3q-.825 0-1.412-.587T1 17V6q0-.825.588-1.412T3 4h18q.825 0 1.413.588T23 6v11q0 .825-.587 1.413T21 19h-2v1q0 .425-.288.713T18 21zm-3-4h18V6H3zm3.025-2H18q.3 0 .45-.275t-.05-.525l-3.5-4.675q-.15-.2-.4-.2t-.4.2L11 13.5l-2.1-2.525q-.15-.2-.387-.187T8.125 11l-2.5 3.2q-.2.25-.062.525t.462.275M3 17V6z");
}

</style>
