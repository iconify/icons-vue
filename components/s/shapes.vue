<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6uya6zdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shapes" /></template>
<style>
.s6uya6zdr {
  fill: currentColor;
  d: path("M4.038 13.963Q2 11.925 2 9t2.038-4.962T9 2t4.963 2.038T16 9t-2.037 4.963T9 16t-4.962-2.037M8 20v-2.05q.25.025.5.038T9 18q3.75 0 6.375-2.625T18 9q0-.25-.012-.5T17.95 8H20q.825 0 1.413.588T22 10v10q0 .825-.587 1.413T20 22H10q-.825 0-1.412-.587T8 20");
}

</style>
