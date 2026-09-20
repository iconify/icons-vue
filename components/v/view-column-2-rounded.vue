<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc6i50bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-column-2-rounded" /></template>
<style>
.tc6i50bex {
  fill: currentColor;
  d: path("M15 21q-.825 0-1.412-.587T13 19V5q0-.825.588-1.412T15 3h4q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h4q.825 0 1.413.588T11 5v14q0 .825-.587 1.413T9 21z");
}

</style>
