<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbc0apt3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rear-camera" /></template>
<style>
.qbc0apt3l {
  fill: currentColor;
  d: path("M17.213 7.713Q17.5 7.425 17.5 7t-.288-.712T16.5 6t-.712.288T15.5 7t.288.713T16.5 8t.713-.288M13 19h7V5h-7zm-9 2q-.825 0-1.412-.587T2 19v-6h4.2l-1.6 1.6L6 16l4-4l-4-4l-1.4 1.4L6.2 11H2V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21z");
}

</style>
