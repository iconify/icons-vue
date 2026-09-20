<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfj39k6fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:travel-luggage-and-bags-rounded" /></template>
<style>
.xfj39k6fw {
  fill: currentColor;
  d: path("M11 6h2V4h-2zm-2.625 5.213Q6.65 10.425 5 9.45V8q0-.825.588-1.412T7 6h2V3q0-.425.288-.712T10 2h4q.425 0 .713.288T15 3v3h2q.825 0 1.413.588T19 8v1.45q-1.65.975-3.375 1.763T12 12t-3.625-.788M7 21q-.825 0-1.412-.587T5 19v-7.3q1.4.85 2.888 1.45t3.112.8V14q0 .425.288.713T12 15t.713-.288T13 14v-.05q1.625-.2 3.113-.8T19 11.7V19q0 .825-.587 1.413T17 21q0 .425-.288.713T16 22q-.4 0-.562-.363T15 21H9q0 .425-.288.713T8 22q-.4 0-.562-.363T7 21");
}

</style>
