<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmsqvwbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pivot-table-chart" /></template>
<style>
.kmsqvwbjn {
  fill: currentColor;
  d: path("M10 8V3h9q.825 0 1.413.588T21 5v3zM5 21q-.825 0-1.412-.587T3 19v-9h5v11zM3 8V5q0-.825.588-1.412T5 3h3v5zm10 14l-4-4l4-4l1.4 1.4l-1.55 1.6H15q.825 0 1.413-.587T17 15v-2.2l-1.6 1.6L14 13l4-4l4 4l-1.4 1.4l-1.6-1.6V15q0 1.65-1.175 2.825T15 19h-2.15l1.55 1.6z");
}

</style>
