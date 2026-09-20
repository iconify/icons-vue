<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_pcbapp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-open-outline" /></template>
<style>
.yw_pcbapp {
  fill: currentColor;
  d: path("M11.5 16V8l-4 4zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm11-2h3V5h-3zm-2 0V5H5v14zm2 0h3z");
}

</style>
