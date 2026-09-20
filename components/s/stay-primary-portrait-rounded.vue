<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvyifzbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stay-primary-portrait-rounded" /></template>
<style>
.gvyifzbnn {
  fill: currentColor;
  d: path("M12 17q-.425 0-.712-.288T11 16t.288-.712T12 15t.713.288T13 16t-.288.713T12 17m0-4q-.425 0-.712-.288T11 12V8q0-.425.288-.712T12 7t.713.288T13 8v4q0 .425-.288.713T12 13M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v18q0 .825-.587 1.413T17 23zm0-5h10V6H7z");
}

</style>
