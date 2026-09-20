<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsb_xybei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-sign-outline" /></template>
<style>
.qsb_xybei {
  fill: currentColor;
  d: path("M7 12h10v-2H7zm0-4h10V6H7zm4 12v-2.75q-.45-.275-.725-.725T10 15.5q0-.825.575-1.413T12 13.5q.825 0 1.413.587T14 15.5q0 .575-.275 1.013t-.725.712V20h4q.825 0 1.413.588T19 22H5q0-.825.575-1.412T7 20zm-6-4q-.825 0-1.412-.587T3 14V4q0-.825.588-1.412T5 2h14q.825 0 1.413.588T21 4v10q0 .825-.587 1.413T19 16h-3.025q.05-.5-.012-1.012T15.7 14H19V4H5v10h3.275q-.2.475-.25.988t0 1.012z");
}

</style>
