<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9sbo6lre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-cancel" /></template>
<style>
.h9sbo6lre {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm2.65-7.25L12 13.425l2.325 2.325l1.425-1.4L13.4 12l2.35-2.325l-1.425-1.425L12 10.6L9.65 8.25l-1.4 1.425L10.575 12L8.25 14.35z");
}

</style>
