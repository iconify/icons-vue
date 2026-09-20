<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo1wezplb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:responsive-layout-outline-rounded" /></template>
<style>
.lo1wezplb {
  fill: currentColor;
  d: path("M3 19v-9q0-.825.588-1.412T5 8h3V5q0-.825.588-1.412T10 3h9q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21H5q-.825 0-1.412-.587T3 19m13 0h3V5h-9v3h4q.825 0 1.413.588T16 10zm-6 0h4v-9h-4zm-5 0h3v-9H5z");
}

</style>
