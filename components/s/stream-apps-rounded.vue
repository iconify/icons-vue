<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8sqbbbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stream-apps-rounded" /></template>
<style>
.n8sqbbbyh {
  fill: currentColor;
  d: path("m16 15l-1.15 1.15q-.25.25-.55.125T14 15.8V9q0-.425.288-.712T15 8h7q.425 0 .713.288T23 9v5q0 .425-.288.713T22 15zm-9 8q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3q0 .425-.288.713T18 7t-.712-.288T17 6H7v12h10q0-.425.288-.712T18 17t.713.288T19 18v3q0 .825-.587 1.413T17 23z");
}

</style>
