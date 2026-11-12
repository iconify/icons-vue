<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0qyqk8cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-portrait-short" /></template>
<style>
.w0qyqk8cf {
  fill: currentColor;
  d: path("M4.15 17q-1.05 0-1.65-.862t-.15-1.813q.725-1.55 1.5-4.112T4.9 4.9q.075-.8.638-1.35T6.9 3h.075V2h3v1H14V2h3v1q.825 0 1.413.588T19 5q0 1.075-.337 2.538t-.85 2.974t-1.125 2.938t-1.163 2.4q-.325.575-.85.863t-1.1.287zm2.825 4q-.825 0-1.412-.587T4.975 19h8.6q1.475 0 2.388-.675T17.3 16.8q.425-.875.875-1.787T19 13.125V19q0 .825-.588 1.413T17 21z");
}

</style>
