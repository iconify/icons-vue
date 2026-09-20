<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg8095b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-sensor-hi" /></template>
<style>
.xg8095b-d {
  fill: currentColor;
  d: path("M8 21q-.825 0-1.412-.587T6 19V5q0-.825.588-1.412T8 3h8q.825 0 1.413.588T18 5v14q0 .825-.587 1.413T16 21zm4.713-13.288Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288M0 17v-7h2v7zm3-3V7h2v7zm19 0V7h2v7zm-3 3v-7h2v7z");
}

</style>
