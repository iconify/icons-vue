<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ab7cc_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vignette-2" /></template>
<style>
.g0ab7cc_n {
  fill: currentColor;
  d: path("M16.25 16.25Q18 14.5 18 12t-1.75-4.25T12 6T7.75 7.75T6 12t1.75 4.25T12 18t4.25-1.75M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
