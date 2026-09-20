<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gunk9rbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:position-bottom-left-outline-rounded" /></template>
<style>
.gunk9rbco {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14zm2.5 12h6q.625 0 1.063-.437T15 15.5t-.437-1.062T13.5 14h-6q-.625 0-1.062.438T6 15.5t.438 1.063T7.5 17");
}

</style>
