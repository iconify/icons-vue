<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9okkjlhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sticky-note-outline-rounded" /></template>
<style>
.x9okkjlhs {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v10.175q0 .4-.15.763t-.425.637l-3.85 3.85q-.275.275-.638.425t-.762.15zm10-2v-2q0-.825.588-1.412T17 15h2V5H5v14zm-4-9v5q0 .425.288.713T12 16t.713-.288T13 15v-5h2q.425 0 .713-.288T16 9t-.288-.712T15 8H9q-.425 0-.712.288T8 9t.288.713T9 10zm-6 9V5z");
}

</style>
