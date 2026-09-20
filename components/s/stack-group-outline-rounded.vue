<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqyg-dbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-group-outline-rounded" /></template>
<style>
.aqyg-dbvq {
  fill: currentColor;
  d: path("M10 22q-.825 0-1.412-.587T8 20v-4H4q-.825 0-1.412-.587T2 14V4q0-.825.588-1.412T4 2h10q.825 0 1.413.588T16 4v4h4q.825 0 1.413.588T22 10v10q0 .825-.587 1.413T20 22zm0-2h10V10h-4q-.825 0-1.412-.587T14 8V4H4v10h4q.825 0 1.413.588T10 16zm2-8");
}

</style>
