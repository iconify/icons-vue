<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w32c3p1sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-day-outline" /></template>
<style>
.w32c3p1sz {
  fill: currentColor;
  d: path("M3 20v-2h18v2zM3 6V4h18v2zm2 10q-.825 0-1.412-.587T3 14v-4q0-.825.588-1.412T5 8h14q.825 0 1.413.588T21 10v4q0 .825-.587 1.413T19 16zm0-2h14v-4H5zm0-4v4z");
}

</style>
