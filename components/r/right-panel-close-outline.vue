<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8k2s1wzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-close-outline" /></template>
<style>
.g8k2s1wzr {
  fill: currentColor;
  d: path("M7.5 8v8l4-4zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm11-2h3V5h-3zm-2 0V5H5v14zm2 0h3z");
}

</style>
