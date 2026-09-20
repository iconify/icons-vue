<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arzar00ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-chart-rounded" /></template>
<style>
.arzar00ds {
  fill: currentColor;
  d: path("M3 8V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v3zm2 13q-.825 0-1.412-.587T3 19v-9h4.5v11zm11.5 0V10H21v9q0 .825-.587 1.413T19 21zm-7 0V10h5v11z");
}

</style>
