<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbrw1mdlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-bottle-large-outline" /></template>
<style>
.sbrw1mdlg {
  fill: currentColor;
  d: path("M7 20h10v-2h-2v-7h-2V9h4V7H7v2h2v7h2v2H7zm0 2q-.825 0-1.412-.587T5 20v-2q0-.825.588-1.412T7 16v-5q-.825 0-1.412-.587T5 9V7q0-.825.588-1.412T7 5h3V4H9V2h6v2h-1v1h3q.825 0 1.413.588T19 7v2q0 .825-.587 1.413T17 11v5q.825 0 1.413.588T19 18v2q0 .825-.587 1.413T17 22zm5-8.5");
}

</style>
