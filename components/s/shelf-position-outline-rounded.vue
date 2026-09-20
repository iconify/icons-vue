<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x93t8gr7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shelf-position-outline-rounded" /></template>
<style>
.x93t8gr7h {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm14-5H5v3h14zm-2.5-2H19V5h-2.5zM5 14h2.5V5H5zm4.5 0h5V5h-5z");
}

</style>
