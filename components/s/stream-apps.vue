<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3c26kzjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stream-apps" /></template>
<style>
.g3c26kzjy {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v5h-5q-1.25 0-2.125.875T11 11v10h2.825l2-2H19v2q0 .825-.587 1.413T17 23zm6-4v-8q0-.425.288-.712T14 10h7q.425 0 .713.288T22 11v5q0 .425-.288.713T21 17h-6zm-.288-13.288Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288");
}

</style>
