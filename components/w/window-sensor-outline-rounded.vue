<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqy4f6blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-sensor-outline-rounded" /></template>
<style>
.tqy4f6blt {
  fill: currentColor;
  d: path("M22 9q-.425 0-.712-.288T21 8V4q0-.425.288-.712T22 3t.713.288T23 4v4q0 .425-.288.713T22 9M3 19V5q0-.825.588-1.412T5 3h12q.825 0 1.413.588T19 5v14q0 .825-.587 1.413T17 21H5q-.825 0-1.412-.587T3 19m2-8h5v-.5q0-.2.15-.35t.35-.15h1q.2 0 .35.15t.15.35v.5h5V5H5zm0 8h12v-6H5zm0 0h12z");
}

</style>
