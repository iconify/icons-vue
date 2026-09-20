<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkg310_tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-off-outline-rounded" /></template>
<style>
.mkg310_tc {
  fill: currentColor;
  d: path("M19.8 22.6L1.4 4.2q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l18.4 18.4q.275.275.275.7t-.275.7t-.7.275t-.7-.275M7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9v2.9q0 .5-.312.75T18 14.8t-.687-.262t-.313-.763V3H5q0-.825.588-1.412T7 1m5.713 4.713Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288M7 23q-.825 0-1.412-.587T5 21V5l2 2v14h10v-4l2 2v2q0 .825-.587 1.413T17 23zm6.9-11.7");
}

</style>
