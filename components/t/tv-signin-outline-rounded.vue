<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gznfvkbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-signin-outline-rounded" /></template>
<style>
.gznfvkbth {
  fill: currentColor;
  d: path("M4 19q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v12q0 .825-.587 1.413T20 19h-4v1q0 .425-.288.713T15 21H9q-.425 0-.712-.288T8 20v-1zm0-2h16V5H4zm0 0V5zm4-2h8v-.55q0-1.125-1.1-1.787T12 12t-2.9.663T8 14.45zm5.413-4.587Q14 9.825 14 9t-.587-1.412T12 7t-1.412.588T10 9t.588 1.413T12 11t1.413-.587");
}

</style>
