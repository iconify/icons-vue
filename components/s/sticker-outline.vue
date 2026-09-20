<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn_uqlc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sticker-outline" /></template>
<style>
.qn_uqlc5q {
  fill: currentColor;
  d: path("M11.5 15q1.725 0 3-1.125T16 11.05L8 13.3q.65.8 1.55 1.25t1.95.45m-4.15-3.75L10 10.5q.1-.7-.35-1.225T8.5 8.75q-.625 0-1.062.438T7 10.25q0 .275.1.525t.25.475m6-1.75L16 8.75q.125-.7-.337-1.225T14.5 7q-.625 0-1.062.438T13 8.5q0 .275.1.525t.25.475M16 21H5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v11zm-1-2v-2q0-.825.588-1.412T17 15h2V5H5v14zM5 19V5z");
}

</style>
