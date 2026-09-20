<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uytgejb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-column-2-outline-sharp" /></template>
<style>
.uytgejb2o {
  fill: currentColor;
  d: path("M15 21q-.825 0-1.412-.587T13 19V5q0-.825.588-1.412T15 3h4q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-16v14h4V5zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h4q.825 0 1.413.588T11 5v14q0 .825-.587 1.413T9 21zM5 5v14h4V5zm14 0h-4zM9 5H5z");
}

</style>
