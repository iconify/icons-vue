<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p98s_gzsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sound-detection-glass-break-rounded" /></template>
<style>
.p98s_gzsx {
  fill: currentColor;
  d: path("M3 16V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v.05l-7.5 8.425l-2.575-2.575q-.3-.3-.675-.45t-.75-.15q-.4 0-.763.15t-.662.45zm2 5q-.825 0-1.412-.587T3 19l6.5-6.525l2.5 2.5q.3.3.675.438t.75.137q.425 0 .8-.15t.675-.5L21 8.05V19q0 .825-.587 1.413T19 21z");
}

</style>
