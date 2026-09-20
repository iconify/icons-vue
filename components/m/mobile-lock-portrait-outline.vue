<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s35_vrb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-lock-portrait-outline" /></template>
<style>
.s35_vrb1p {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm0-2h10V3H7zm0 0V3zm2.85-5h4.3q.35 0 .6-.25t.25-.6v-3.3q0-.35-.25-.6t-.6-.25H14v-1q0-.825-.587-1.412T12 8t-1.412.588T10 10v1h-.15q-.35 0-.6.25t-.25.6v3.3q0 .35.25.6t.6.25M11 11v-1q0-.425.288-.712T12 9t.713.288T13 10v1z");
}

</style>
