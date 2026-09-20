<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzsyl4bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-frame-2-outline" /></template>
<style>
.gzsyl4bgj {
  fill: currentColor;
  d: path("M20 10V7h-3V5h3q.825 0 1.413.588T22 7v3zM2 10V7q0-.825.588-1.412T4 5h3v2H4v3zm15 9v-2h3v-3h2v3q0 .825-.587 1.413T20 19zM4 19q-.825 0-1.412-.587T2 17v-3h2v3h3v2z");
}

</style>
