<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfgo2ekzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-arrow-down" /></template>
<style>
.xfgo2ekzv {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm5-7l4-4l-1.4-1.4l-1.6 1.55V8h-2v4.15L9.4 10.6L8 12z");
}

</style>
