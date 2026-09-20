<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwpx257lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-screensaver-outline" /></template>
<style>
.hwpx257lp {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm0-2h10V3H7zm1-6h8l-2.625-3.5L11.5 14l-1.375-1.825zm7.713-5.288Q16 9.425 16 9t-.288-.712T15 8t-.712.288T14 9t.288.713T15 10t.713-.288M7 21V3z");
}

</style>
