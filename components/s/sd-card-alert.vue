<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9fg41boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-card-alert" /></template>
<style>
.g9fg41boj {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8l6-6h8q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm6-5q.425 0 .713-.288T13 16t-.288-.712T12 15t-.712.288T11 16t.288.713T12 17m-1-4h2V8h-2z");
}

</style>
