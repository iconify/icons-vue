<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp8gib30z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upcoming-outline" /></template>
<style>
.dp8gib30z {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19v-5q0-.825.588-1.412T4 12h5q0 1.25.875 2.125T12 15t2.125-.875T15 12h5q.825 0 1.413.588T22 14v5q0 .825-.587 1.413T20 21zm0-2h16v-5h-3.4q-.625 1.375-1.862 2.188T12 17t-2.738-.812T7.4 14H4zm13.6-8.2l-1.4-1.4l3.55-3.55l1.4 1.4zm-11.2 0L2.85 7.25l1.4-1.4L7.8 9.4zM11 8V3h2v5zM4 19h16z");
}

</style>
