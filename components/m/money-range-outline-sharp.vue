<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tijh6lr7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:money-range-outline-sharp" /></template>
<style>
.tijh6lr7t {
  fill: currentColor;
  d: path("M5.5 22.5L2 19l3.5-3.5l1.425 1.4l-1.1 1.1h12.35L17.1 16.9l1.4-1.4L22 19l-3.5 3.5l-1.425-1.4l1.1-1.1H5.825L6.9 21.1zM12 11q-1.25 0-2.125-.875T9 8t.875-2.125T12 5t2.125.875T15 8t-.875 2.125T12 11m-9 3V2h18v12zm4-2h10q0-.825.588-1.412T19 10V6q-.825 0-1.412-.587T17 4H7q0 .825-.587 1.413T5 6v4q.825 0 1.413.588T7 12m-2 0V4z");
}

</style>
