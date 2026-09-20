<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0kh5w1lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pregnancy-rounded" /></template>
<style>
.e0kh5w1lx {
  fill: currentColor;
  d: path("M10 21v-4H9q-.425 0-.712-.288T8 16v-6q0-1.25.875-2.125T11 7t2.125.875T14 10q.9.375 1.45 1.2T16 13v3q0 .425-.288.713T15 17h-2v4q0 .425-.288.713T12 22h-1q-.425 0-.712-.288T10 21M9.587 5.413Q9 4.825 9 4t.588-1.412T11 2t1.413.588T13 4t-.587 1.413T11 6t-1.412-.587");
}

</style>
