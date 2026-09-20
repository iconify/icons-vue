<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk2pr9byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-comfy-alt-rounded" /></template>
<style>
.pk2pr9byf {
  fill: currentColor;
  d: path("M8 10H4q-.825 0-1.412-.587T2 8V4q0-.825.588-1.412T4 2h4q.825 0 1.413.588T10 4v4q0 .825-.587 1.413T8 10m0 12H4q-.825 0-1.412-.587T2 20v-4q0-.825.588-1.412T4 14h4q.825 0 1.413.588T10 16v4q0 .825-.587 1.413T8 22m12-12h-4q-.825 0-1.412-.587T14 8V4q0-.825.588-1.412T16 2h4q.825 0 1.413.588T22 4v4q0 .825-.587 1.413T20 10m0 12h-4q-.825 0-1.412-.587T14 20v-4q0-.825.588-1.412T16 14h4q.825 0 1.413.588T22 16v4q0 .825-.587 1.413T20 22");
}

</style>
