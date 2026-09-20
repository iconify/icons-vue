<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrl848w1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-chart-outline" /></template>
<style>
.nrl848w1m {
  fill: currentColor;
  d: path("M19 21H5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21M5 8h14V5H5zm2.5 2H5v9h2.5zm9 0v9H19v-9zm-2 0h-5v9h5z");
}

</style>
