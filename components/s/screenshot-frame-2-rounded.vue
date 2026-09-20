<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snqq3xbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-frame-2-rounded" /></template>
<style>
.snqq3xbae {
  fill: currentColor;
  d: path("M20.288 9.713Q20 9.425 20 9V7h-2q-.425 0-.712-.288T17 6t.288-.712T18 5h2q.825 0 1.413.588T22 7v2q0 .425-.288.713T21 10t-.712-.288M3 10q-.425 0-.712-.288T2 9V7q0-.825.588-1.412T4 5h2q.425 0 .713.288T7 6t-.288.713T6 7H4v2q0 .425-.288.713T3 10m15 9q-.425 0-.712-.288T17 18t.288-.712T18 17h2v-2q0-.425.288-.712T21 14t.713.288T22 15v2q0 .825-.587 1.413T20 19zM4 19q-.825 0-1.412-.587T2 17v-2q0-.425.288-.712T3 14t.713.288T4 15v2h2q.425 0 .713.288T7 18t-.288.713T6 19z");
}

</style>
