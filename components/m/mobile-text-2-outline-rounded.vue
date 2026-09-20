<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz7-xibwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-text-2-outline-rounded" /></template>
<style>
.sz7-xibwd {
  fill: currentColor;
  d: path("M9 12h6q.425 0 .713-.288T16 11t-.288-.712T15 10H9q-.425 0-.712.288T8 11t.288.713T9 12m1 3.5h4q.425 0 .713-.288T15 14.5t-.288-.712T14 13.5h-4q-.425 0-.712.288T9 14.5t.288.713t.712.287M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm0-2h10V3H7zm0 0V3z");
}

</style>
