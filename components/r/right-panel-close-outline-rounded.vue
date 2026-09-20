<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b56ak4g8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-close-outline-rounded" /></template>
<style>
.b56ak4g8t {
  fill: currentColor;
  d: path("M7.5 14.8q0 .35.3.475t.55-.125l2.45-2.45q.3-.3.3-.7t-.3-.7L8.35 8.85q-.25-.25-.55-.125t-.3.475zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm11-2h3V5h-3zm-2 0V5H5v14zm2 0h3z");
}

</style>
